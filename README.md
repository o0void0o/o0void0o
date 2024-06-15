```python
name = "Etienne Swanepoel"

about = "A passionate software developer with a love for coding and collaboration."

interests = [
    "all things computers",
    "mountain biking",
    "music",
    "breathing"
]

stack = [
    "java",
    "python",
    "sql"
]

motto = "do whatever makes you happy, but never at the expence of somebody elses."

def print_bio():
    print(f"### {name}")
    print(about)
    print("\n**Interests:**")
    for interest in interests:
        print(f"- {interest}")
    for astack in stack:
        print(f"- {astack}")
    print(f"\n> {motto}")

```
