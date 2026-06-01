# Peer Review Backend — Project Backlog

A Rails (API-only) backend for a developer peer-review platform. Developers post pull requests, others review them, developers follow people and frameworks to populate a feed, comment on posts, chat in real time, and attach images/videos to posts.

**Stack:** Rails (API mode) · PostgreSQL · Redis · Keycloak (OIDC auth) · Pundit (authorization) · EMQX (MQTT chat) · Sidekiq (background jobs) · Rufus-scheduler (cron) · Active Storage + S3/MinIO (media).