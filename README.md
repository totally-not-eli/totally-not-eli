# 👋 Hi, I'm Eli

> Data & Backend Engineer crafting robust systems that scale.

## 🛠️ About Me
I'm a backend developer specializing in data engineering and distributed systems. My expertise lies in:
- Python
- Rust
- Golang

I thrive in backend development because I enjoy architecting systems that handle complex data flows and solving challenging engineering problems. I also dabble in FE whenever it's needed. I try to structure it based on what's already existing though : D.

## 🔨 What I Do

### 🔄 Data Engineering & ETL
- Design and implement scalable ETL pipelines
- Data warehouse optimization and management
- Real-time data processing systems
- Custom web crawlers for efficient data retrieval
- Data validation and cleaning protocols

### 🏗️ Backend Architecture
- RESTful APIs development (Will dabble on GraphQL soon)
- Authentication & Authorization systems
- Microservices architecture
- Service mesh implementations
- Load balancing and scaling solutions

### 🔍 Developer Experience
I'm passionate about creating developer-friendly systems:
```python
# Like this logger here - would want this on an API too formatted to the endpoint name / function under that endpoint
def log_operation(operation_name):
    def decorator(func):
        @wraps(func)
        async def wrapper(*args, **kwargs):
            logger.info(f"Starting {operation_name}")
            try:
                result = await func(*args, **kwargs)
                logger.info(f"Completed {operation_name}")
                return result
            except Exception as e:
                logger.error(f"Failed {operation_name}: {str(e)}")
                raise
        return wrapper
    return decorator
```

### 🛡️ Best Practices
- Comprehensive logging systems for better debugging
- Custom decorators for code reusability
- Middleware implementations for request tracking
- Error handling and monitoring solutions
- Performance optimization techniques

## 🔭 Current Focus
Building and optimizing:
- High-performance data retrieval systems
- Scalable web crawlers
- Real-time data processing pipelines
- API gateway implementations

## 📊 GitHub Stats

<div>
    <img height="170" align="left" src="https://github-readme-stats.vercel.app/api?username=totally-not-eli&count_private=true&include_all_commits=true&show_icons=true&theme=dark" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=totally-not-eli&layout=compact&theme=dark" />
</div>

## 🚀 Tech Stack
```python
tech_stack = {
    "Languages": ["Python", "Rust", "Golang", "JavaScript", "TypeScript"],
    "Databases": ["PostgreSQL", "MongoDB", "Redis", "Elasticsearch", "NoSQL", "MySQL"],
    "Tools": ["Docker", "Kubernetes", "Apache Airflow"],
    "Cloud": ["AWS", "GCP"],
    "FE + BE Frameworks": ["FastAPI", "Flask", "NextJS", "NuxtJS", "React", "Vue"]
}
```

## 🔧 Core Competencies
- Distributed Systems Design
- Data Pipeline Architecture
- API Development & Integration
- Authentication Systems
- Performance Optimization
- System Monitoring & Logging
- Developer Tooling

## 📫 Connect With Me
Interested in:
- Data engineering, Software Development and AI Integrations (LangChain FTWWW)
- Backend system architecture
- Performance optimization
- Developer experience improvements'

<!--
Keeping these for future updates:
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
