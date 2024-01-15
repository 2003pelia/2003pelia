developer = DeveloperProfile(
    name="Preston Elia",
    university="SUNY Oswego",
    languages=["Python", "Powershell", "Java", "C#"],
    tools=["VS Code", "Git"]
)

projects_info = developer.display_projects()
skills_info = developer.display_skills()
connect_info = developer.connect()
collaborate_info = developer.collaborate(ideas="Let's create something amazing!")

print(projects_info)
print(skills_info)
print(connect_info)
print(collaborate_info)
