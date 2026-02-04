duy@dev-server:~$ whoami

Duy Nguyen

duy@dev-server:~$ cat /etc/profile.d/developer.sh

# System Information
┌─────────────────────────────────────────────────────────────┐
│ Username    : Duy Nguyen                                    │
│ Role        : Software Engineer                             │
│ Location    : Ho Chi Minh City, Vietnam                     │
│ Uptime      : 2+ years in production                        │
└─────────────────────────────────────────────────────────────┘

# Network Configuration
EMAIL       : ndtduy.work@gmail.com
PORTFOLIO   : https://me.ndtduy.live
GITHUB      : https://github.com/thanhduy1706
LINKEDIN    : https://linkedin.com/in/thanhduy1706

duy@dev-server:~$ ls -la ~/projects/

total 3
drwxr-xr-x  5 duy  staff   160 Feb  4 2025 .
drwxr-xr-x  8 duy  staff   256 Feb  4 2025 ..

drwxr-xr-x  12 duy  staff  384 Dec 15 2024 iu-libbuddy/
  ├── Description: AI-powered meeting room booking with RAG chatbot
  ├── Type: Bachelor's Thesis Project
  ├── Status: ✓ Production (https://iulib.ndtduy.live)
  ├── Metrics:
  │   ├── Users: 1,200+ registered
  │   ├── Bookings: 8,000+ processed
  │   ├── AI Accuracy: 86% (baseline: 62%)
  │   ├── API Response: <200ms
  │   └── Satisfaction: 4.6/5 ⭐
  └── Stack: React Native | Next.js | NestJS | PostgreSQL | RabbitMQ
            LangChain | OpenAI | Docker | Jenkins | Cloudflare

drwxr-xr-x  8 duy  staff  256 Jun 20 2024 intellispace/
  ├── Description: Collaborative workspace with real-time communication
  ├── Status: ✓ Production (https://intelli-space.vercel.app)
  └── Stack: Next.js | Spring Boot | PostgreSQL | Azure

drwxr-xr-x  6 duy  staff  192 Dec 10 2023 datavizx/
  ├── Description: Interactive data visualization with chart analytics
  └── Stack: React | Chart.js | Node.js | MongoDB



duy@dev-server:~$ dpkg -l | grep tech-stack

ii  react              18.2.0    JavaScript library for building user interfaces
ii  nextjs             14.1.0    React framework for production
ii  react-native       0.73.0    Framework for building native mobile apps
ii  typescript         5.3.3     Typed superset of JavaScript
ii  nodejs             20.11.0   JavaScript runtime built on Chrome's V8
ii  nestjs             10.3.0    Progressive Node.js framework
ii  postgresql         16.1      Advanced open source database
ii  mongodb            7.0.5     NoSQL database program
ii  redis              7.2.4     In-memory data structure store
ii  docker             25.0.0    Container platform
ii  jenkins            2.440.1   Automation server
ii  nginx              1.25.3    HTTP and reverse proxy server
ii  openai-api         1.10.0    OpenAI API client
ii  langchain          0.1.0     LLM application framework



duy@dev-server:~$ systemctl status developer.service

● developer.service - Software Engineer Service
   Loaded: loaded (/etc/systemd/system/developer.service; enabled)
   Active: active (running) since 2021-09-01 08:00:00 ICT; 3 years ago
     Docs: https://me.ndtduy.live
 Main PID: 1706 (duy-nguyen)
    Tasks: ∞
   Memory: ∞
   CGroup: /system.slice/developer.service
           ├─ frontend: React, Next.js, React Native, TypeScript
           ├─ backend: Node.js, NestJS, PostgreSQL, MongoDB
           ├─ devops: Docker, Jenkins, Linux, CI/CD
           └─ ai: OpenAI, LangChain, RAG

Feb 04 08:00:00 dev-server systemd[1]: Started Software Engineer Service
Feb 04 08:00:01 dev-server developer[1706]: ✓ Frontend skills loaded
Feb 04 08:00:02 dev-server developer[1706]: ✓ Backend skills loaded
Feb 04 08:00:03 dev-server developer[1706]: ✓ DevOps skills loaded
Feb 04 08:00:04 dev-server developer[1706]: ✓ AI integration ready
Feb 04 08:00:05 dev-server developer[1706]: Status: Ready for production



duy@dev-server:~$ curl -s https://api.github.com/users/thanhduy1706 | jq '{commits, repositories, contributions}'

{
  "commits": "500+",
  "repositories": "20+",
  "contributions": "Daily",
  "streak": "Active"
}



duy@dev-server:~$ cat /etc/motd

╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║  Welcome to Duy's Developer Server                          ║
║  Ubuntu 22.04.3 LTS | Kernel 5.15.0-91-generic             ║
║                                                              ║
║  📧  Email    : ndtduy.work@gmail.com                       ║
║  🌐  Portfolio: https://me.ndtduy.live                      ║
║  💼  LinkedIn : https://linkedin.com/in/thanhduy1706        ║
║  🐙  GitHub   : https://github.com/thanhduy1706             ║
║                                                              ║
║  System Status: ✓ All services running                      ║
║  Load Average : 40% performance boost                       ║
║  Uptime       : 99.9%                                        ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝

duy@dev-server:~$ sudo systemctl start collaboration.service
[sudo] password for collaboration: ●●●●●●●●●●●●●●●●●●●●●●●●●●●●●●●●●●●●●●

✓ Collaboration service started
✓ Ready to build amazing projects together!

duy@dev-server:~$ █





Profile Views

