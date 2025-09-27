class FullStackDeveloper:
    def __init__(self):
        self.name = "YourName"
        self.roles = ["Software Engineer", "Web Developer", "Tech Educator"]
        self.philosophy = "#LearningInPublic"
        self.specialties = {
            "web_development": "Full-stack applications",
            "data_analytics": "Interactive visualizations", 
            "content_creation": "Educational tech content"
        }
        
    @property
    def current_stack(self):
        return {
            "frontend": "React, TypeScript, Tailwind",
            "backend": "Node.js, Express, MongoDB",
            "data_tools": "Python, Pandas, Tableau",
            "devops": "Docker, CI/CD, Vercel"
        }
    
    def build_project(self, idea: str) -> str:
        return f"🚀 Building: {idea} | Stack: {self.current_stack}"
    
    def teach_concept(self, topic: str) -> str:
        return f"🎥 Creating tutorial: {topic} | #LearningInPublic"

# Instantiate my developer journey
dev_journey = FullStackDeveloper()
