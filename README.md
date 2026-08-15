<div align="center">

# Hey, I'm Musthaq Asim

Backend-leaning dev who somehow ended up shipping a full React frontend too.
I build self-hosted microservices for fun and keep turning a hobby project into a real platform.

<br>

### Tech I use

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Netflix Eureka](https://img.shields.io/badge/Netflix%20Eureka-E50914?style=flat-square&logo=netflix&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

</div>

<br>

## Projects

### Re:muria
> Companion app for Honkai: Star Rail, live at [remuria.net](https://remuria.net)

- Look up any UID to see character stats, relic builds and rankings
- A small microservices setup: a gateway with Discord login, a game data backend, a translation service, and a discovery and admin layer built on Netflix Eureka
- Data spread across MongoDB, Neo4j and Redis, containerized and self-hosted across two nodes for redundancy and backups

| Repo | Role |
|---|---|
| [Aquila](https://github.com/Amphorous/Aquila) | API gateway + Discord login |
| [Delta-me13](https://github.com/Amphorous/Delta-me13) | Game data backend |
| [Delphi](https://github.com/Amphorous/Delphi) | Service discovery + deploy hub |
| [CelestiaAdmin](https://github.com/Amphorous/CelestiaAdmin) | Monitoring dashboard |
| [Translator](https://github.com/Amphorous/Translator) | Localization service |
| [Delta-me13-Frontend](https://github.com/Amphorous/Delta-me13-Frontend) | React frontend |

**Stack:** `Java` `Spring Boot` `Spring Cloud Gateway` `Netflix Eureka` `React` `Redux` `MongoDB` `Neo4j` `Redis` `Docker` `nginx` `GitHub Actions`

### zandar-env
> Local AI coding copilot I built to help develop Re:muria

**Repo:** [MdMusthaqAsim/zandar-env](https://github.com/MdMusthaqAsim/zandar-env)

- Ingests all of Re:muria's repos into a vector store, chunked and tagged by file and service
- Runs as a multi-mode LangGraph agent: a debugging mode that traces issues across services, a builder mode that writes code, and a general Q&A mode
- Local-first inference through Ollama, with a cloud model as a fallback

**Stack:** `Python` `LangChain` `LangGraph` `ChromaDB` `Ollama`

<br>
