# Python Config Bio

\`\`\`python
# Your Name
name = "Your Name"

# A Few Words About You
about = "A passionate Python developer with a love for coding and a hunger for knowledge."

# Your Interests
interests = [
    "Coding in Python",
    "Reading tech blogs",
    "Exploring new libraries",
    "Contributing to open-source projects"
]

# Your Favorite Quote
quote = "The code is the truth, and the truth shall set you free."

# Print Your Bio
def print_bio():
    print(f"### {name}")
    print(about)
    print("\n**Interests:**")
    for interest in interests:
        print(f"- {interest}")
    print(f"\n> {quote}")

# Run the Bio
print_bio()
\`\`\`

And when executed, it will print out your bio like this:

\`\`\`
### Your Name
A passionate Python developer with a love for coding and a hunger for knowledge.

**Interests:**
- Coding in Python
- Reading tech blogs
- Exploring new libraries
- Contributing to open-source projects

> The code is the truth, and the truth shall set you free.
\`\`\`
