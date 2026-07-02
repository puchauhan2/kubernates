
                Browser
                    │
                    ▼
         NGINX Ingress Controller
                    │
                    ▼
      ClusterIP Service (WordPress)
                    │
         ┌──────────┼──────────┐
         ▼          ▼          ▼
      WP Pod     WP Pod     WP Pod
                    │
                    ▼
      Headless Service (MySQL)
                    │
                    ▼
      MySQL StatefulSet (mysql-0)
                    │
                    ▼
           Persistent Volume

