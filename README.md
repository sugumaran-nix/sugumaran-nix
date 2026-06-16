class Sugumaran:
    def __init__(self):
        self.name        = "Sugumaran"
        self.username    = "sugumaran-nix"
        self.location    = "Coimbatore, India 🇮🇳"
        self.degree      = "MCA @ Anna University (2024–2026)"
        self.email       = "sugumarankugan@gmail.com"

        self.stack = [
            "Python", "Flask", "JavaScript",
            "TypeScript", "React.js", "Node.js",
            "MySQL", "MongoDB"
        ]

        self.ai_ml = [
            "Hugging Face Transformers",
            "Scikit-learn", "NLP", "TF-IDF"
        ]

        self.currently_learning = [
            "Docker & DevOps pipelines",
            "Advanced React patterns",
            "Deep Learning fundamentals"
        ]

        self.fun_fact = (
            "I built a fake-news detector "
            "before it was cool 🕵️"
        )

    def motto(self):
        return "Build. Break. Learn. Repeat. 🔁"

me = Sugumaran()
print(me.motto())
