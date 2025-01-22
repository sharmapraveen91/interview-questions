# System Design Interview Questions

## 1. **Design a URL Shortener (like Bit.ly)**

- **Explanation:** Design a system that takes a long URL and returns a shortened version. The system should be able to handle a high number of requests, ensure unique short URLs, track usage, and redirect to the original URL when accessed.

- **Key considerations:**
  - Unique mapping between short and long URLs.
  - Hashing mechanism for generating short URLs.
  - Scalability to handle billions of URLs.
  - Database design (consider using a NoSQL database).
  - Security and potential collisions.
  - Analytics (tracking how often a short URL is accessed).

---

## 2. **Design a Rate Limiter**

- **Explanation:** Design a system that limits how many requests a user can make to an API in a given time period. For example, limit to 100 requests per minute per user.

- **Key considerations:**
  - Time window (sliding window, fixed window, token bucket).
  - Distributed rate limiting across multiple instances of your service.
  - Handling burst traffic and ensuring low latency.
  - Scalability and high availability.
  - Handling "out of order" requests.

---

## 3. **Design a File Storage System (like Google Drive, Dropbox)**

- **Explanation:** Design a system that allows users to upload, store, and share files. The system should handle file versioning, scalability, metadata storage, and sharing permissions.

- **Key considerations:**
  - Storage architecture (object storage, file systems).
  - File uploads and download speed.
  - File deduplication.
  - Access control (permissions and sharing).
  - Handling large files and file chunks.
  - Handling metadata for each file (size, owner, version).

---

## 4. **Design a Social Media Feed (like Facebook News Feed)**

- **Explanation:** Design a system that shows users a personalized feed of posts and updates. The system should be scalable and capable of serving feeds to millions of users.

- **Key considerations:**
  - Data storage and indexing (SQL vs NoSQL).
  - News feed ranking algorithms (based on relevance, recency, etc.).
  - Caching the feed for faster access.
  - Handling large-scale writes and updates.
  - Real-time updates to the feed.
  - Handling multimedia content (images, videos).
  - Data consistency and eventual consistency.
  
---

## 5. **Design a Messaging System (like WhatsApp or Slack)**

- **Explanation:** Design a real-time messaging system with features like one-on-one chats, group chats, message history, and real-time notifications.

- **Key considerations:**
  - Real-time communication (WebSockets, HTTP2).
  - Message storage and retrieval (SQL vs NoSQL).
  - Scaling for millions of users.
  - Handling message delivery guarantees (at least once, exactly once).
  - Notification system for real-time updates.
  - Message encryption and security.
  - Syncing across multiple devices for the same user.

---

## 6. **Design a Video Streaming Service (like YouTube or Netflix)**

- **Explanation:** Design a system that allows users to upload, store, and stream video content efficiently at scale.

- **Key considerations:**
  - Efficient storage of large video files (object storage).
  - Video encoding, compression, and format handling.
  - Adaptive bitrate streaming for varying network conditions (HLS, DASH).
  - Content delivery network (CDN) for global distribution.
  - Scalability for millions of concurrent users.
  - Video recommendations based on user behavior (optional).
  - Caching frequently watched videos for faster access.

---

## 7. **Design a Search Engine (like Google Search)**

- **Explanation:** Design a scalable search engine that can index web pages and return relevant search results based on user queries.

- **Key considerations:**
  - Web crawling and indexing algorithms.
  - Ranking algorithm (PageRank, TF-IDF).
  - Distributed search architecture for scalability.
  - Handling of various data sources and media types (text, images).
  - Data storage for indexed content (elasticsearch, big data tools).
  - Caching popular queries and search results.
  - Ranking and personalization of search results.
  
---

## 8. **Design an Online Bookstore (like Amazon)**

- **Explanation:** Design an e-commerce system for selling books with features like product catalogs, shopping carts, order processing, and payment integration.

- **Key considerations:**
  - Product catalog storage (SQL or NoSQL).
  - Shopping cart and user session management.
  - Scalability for product listings and user transactions.
  - Real-time inventory updates.
  - Order management and fulfillment.
  - Payment processing and security.
  - Recommendation system for books.

---

## 9. **Design a Content Delivery Network (CDN)**

- **Explanation:** Design a CDN that caches and serves content to users from servers located close to their geographical location.

- **Key considerations:**
  - Caching strategies (TTL, cache invalidation).
  - Geographically distributed edge servers.
  - Load balancing between servers.
  - Data replication and synchronization across regions.
  - Handling large media files (images, videos).
  - Ensuring low latency and high availability.
  - Security features like DDoS protection.

---

## 10. **Design a Ticket Booking System (like Movie Ticketing System)**

- **Explanation:** Design a system for booking tickets for movies or events, including seat selection, booking confirmation, and payment.

- **Key considerations:**
  - Seat selection system (availability checking, locking seats during booking).
  - Transaction management (to prevent double booking).
  - High availability and fault tolerance.
  - Real-time updates on seat availability.
  - Integration with payment gateways.
  - Scalability to handle spikes in booking activity.
  
---

## 11. **Design an API Gateway for Microservices Architecture**

- **Explanation:** Design an API gateway that routes requests to various microservices, handles authentication, rate limiting, and provides logging and monitoring.

- **Key considerations:**
  - Load balancing between microservices.
  - Authentication and authorization (OAuth, JWT).
  - Rate limiting and throttling.
  - Request logging, monitoring, and tracing (e.g., using OpenTelemetry).
  - Service discovery (e.g., using Consul or Eureka).
  - Fault tolerance and retries.

---

## 12. **Design a Notification System (like Email/SMS notifications)**

- **Explanation:** Design a system that sends notifications to users via multiple channels (email, SMS, push notifications).

- **Key considerations:**
  - Multi-channel support (email, SMS, push).
  - Message queuing and delivery (e.g., using Kafka).
  - Handling delivery failures and retries.
  - User preferences (opt-in/opt-out).
  - Real-time vs batch notification delivery.
  - Scalability to handle large volumes of notifications.

---

## 13. **Design a Distributed File System**

- **Explanation:** Design a distributed file system that allows users to store and access files across a cluster of machines.

- **Key considerations:**
  - File storage and retrieval (replication, partitioning).
  - File metadata management (directory structure, file attributes).
  - Fault tolerance and replication strategies (e.g., replication factor).
  - Data consistency (CAP theorem considerations).
  - Access control and security.

---

## 14. **Design a Collaborative Real-Time Document Editing System (like Google Docs)**

- **Explanation:** Design a system that allows multiple users to collaboratively edit a document in real-time.

- **Key considerations:**
  - Real-time data synchronization (WebSockets, Operational Transformation, CRDTs).
  - Conflict resolution for simultaneous edits.
  - Permissions and versioning.
  - Data storage and retrieval (handling large documents).
  - Scalability to support thousands of concurrent users.

---

## 15. **Design a System for Live Sports Score Updates**

- **Explanation:** Design a system that tracks and updates live sports scores in real-time for a large audience.

- **Key considerations:**
  - Real-time updates (WebSockets, Server-Sent Events).
  - Data ingestion from external sources (sports feeds, APIs).
  - Caching frequently updated scores.
  - Scaling for high-volume traffic spikes.
  - Multi-platform support (mobile, web).

---

These system design interview questions test your ability to design scalable, efficient, and reliable systems while also requiring knowledge of architectural patterns and trade-offs. When solving these problems, you’ll need to think about **scalability**, **fault tolerance**, **high availability**, **data consistency**, and **performance**.

Feel free to save or share this markdown file for interview preparation or as a reference! Let me know if you need additional questions or further explanations.
