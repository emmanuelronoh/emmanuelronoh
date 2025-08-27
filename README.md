 👋 Hi there, I'm Emmanuel Kipkirui!

class SoftwareEngineer:
    def __init__(self):
        self.name = "Emmanuel Kipkirui"
        self.title = "Software Engineer"
        self.passion = "solving complex problems, building innovative solutions, and creating impactful projects"

        self.current_focus = ["Mastering Software Development", "Building interactive applications"]
        self.exciting_projects = [
            "Developing e-commerce platforms that redefine online shopping",
            "Building educational tools to make learning seamless",
            "Designing adventure games to entertain and educate kids"
        ]
        self.currently_learning = ["React.js for dynamic UIs", "Advanced Backend Development"]
        self.ask_me_about = ["Software engineering best practices", "Web development tools & frameworks", "Crafting user-friendly applications from scratch"]

        self.contact = {
            "email": "erono036@gmail.com",
            "linkedin": "https://www.linkedin.com/in/emmanuel-kipkirui-9a4b8831a/",
            "github": "https://github.com/emmanuelronoh",
            "portfolio": "https://emmanuel-kipkirui-portfolio-brown.vercel.app/"
        }

        self.tech_stack = {
            "languages": ["JavaScript", "Python", "HTML", "CSS"],
            "frontend": ["React.js", "Bootstrap"],
            "backend": ["Django", "JSON Server"],
            "tools": ["Git & GitHub", "Visual Studio Code", "MySQL", "Postman", "Figma"]
        }

        self.github_stats = {
            "stats_image": "https://github-readme-stats.vercel.app/api?username=emmanuelronoh&show_icons=true&theme=radical",
            "top_languages": "https://github-readme-stats.vercel.app/api/top-langs/?username=emmanuelronoh&layout=compact&theme=radical"
        }

        self.featured_projects = {
            "Meal Magic Recipe App": {
                "url": "meal-magic-recipe-app.vercel.app",
                "features": [
                    "Diverse recipes from different cultures",
                    "Save favorite recipes for quick access",
                    "Purchase premium recipes securely via PayPal"
                ]
            },
            "Near Shop": {
                "url": "https://e-commerce-website-kappa-snowy.vercel.app/",
                "features": [
                    "Secure user authentication and product management",
                    "Dynamic shopping cart with dark mode"
                ]
            },
            "Tic Tac Toe Game": {
                "url": "react-game-sable.vercel.app",
                "features": [
                    "Classic 3x3 grid gameplay for two players",
                    "Smooth animations and modern UI"
                ]
            }
        }

    def introduce(self):
        print(f"Hi, I'm {self.name}, a passionate {self.title}.")
        print(f"I love {self.passion}.")
        print("Currently focusing on:", ", ".join(self.current_focus))
        print("Projects I'm excited about:", "; ".join(self.exciting_projects))
        print("Learning:", ", ".join(self.currently_learning))
        print("Ask me about:", ", ".join(self.ask_me_about))
        print("Contact me via email:", self.contact["email"])

 Run the profile
if __name__ == "__main__":
    me = SoftwareEngineer()
    me.introduce()
