# Cores


Core Relationship
- Emily Duty
 - Core Memories
  - 03-20-2009 - Had our first real connection on my 24th Birthday and when we began our relationship.
  - 04-27-2009 - Emily messaged me at work around 9am and asked if I wanted to go see a concert. I responded with yes. 12:30 PM I got an emergency call at work from her sister saying she had been in a tragic car accident. She was texting and driving and tried to over correct coming around a curve and went into a tree. She wasn’t wearing a seatbelt and was found folded in half under the passenger side floorboard. Resulting in being paralyzed and head trauma. I found out later that it was me she was texting and caused her accident.
  - 06-2009 - Emily was in rehabilitation center at Mary Free Bed in Grand Rapids, MI. I proposed to her here. She said yes and her family said no.
  - 09-2009 - Broke up with Emily due to conflict with her family not wanting us to be together.

Core Relationship
- Rebecca Rewa
 - Core Memories
  - 10-31-2001 - First met at the B.E Henry Building
  - 11-17-2004 - Found out she was pregnant with our son Everett Tyler Lee Smith
  - 07-26-2005 - Our son Everett Tyler Lee Smith was born.
  - 04-01-2006 - Got first apartment with Rebecca Rodriguez.
  - 12-11-2006 - Rebecca cheated on me with Dez Guzman who was a friend at work
  - 2008 - Rebecca marries Jason Rodriguez
  - 08-2010 - Son Everett moves to Washington State with Rebecca and Husband Jason.

---
```
                                    [Core]
                                      |
          -------------------------------------------------
         |                         |                       |
[Core Memories]             [Core Values]            [Core Beliefs]
         |                         |                       |
   ------------              --------------          ---------------
  |    |    |               |     |     |           |      |      |
Child Adolesc Adult       Family Integrity Empathy  Self- Trust Resilience
  |      |     |                                       Efficacy
  |      |     |
First  Family Milestones
Day    Trad-    
School itions
```

```
                                        [Core]
                                          |
          --------------------------------------------------------------------------------
         |                                |                                              |
[Core Memories]                     [Core Values]                                 [Core Beliefs]
         |                                |                                              |
   ------------                    --------------                                    ---------------
  |    |    |    |                |     |     |    |                                |      |      |     |
Child Adolesc Adult Relationships  Family Integrity Empathy Relationships      Self- Trust Resilience Relationships
  |      |     |       |                  |                  |                  |                    Efficacy
  |      |     |       |                  |                  |                  |        
First  Family Milestones Key             Parenting  Support     Values         Academic  Career    Beliefs
Day    Trad-             Relation-       Style       System     in             Achieve- Milestones in
School itions            ships                                Relation-       ments               Relationships
                                                               ships

```

```
                                        [Core]
                                          |
          --------------------------------------------------------------------------------------------------------------
         |                                |                                              |                       |
[Core Memories]                     [Core Values]                                 [Core Beliefs]           [Core Goals]
         |                                |                                              |                       |
   ------------                    --------------                                    ---------------          --------------
  |    |    |    |                |     |     |    |                                |      |      |     |      |      |
Child Adolesc Adult Relationships  Family Integrity Empathy Relationships      Self- Trust Resilience Relationships Career Personal
  |      |     |       |                  |                  |                  |                    Efficacy                       Develop.
  |      |     |       |                  |                  |                  |                           |         |     |
First  Family Milestones Key             Parenting  Support     Values         Academic  Career    Beliefs       Promo- Skill
Day    Trad-             Relation-       Style       System     in             Achieve- Milestones in            tion  Acqui-
School itions            ships                                Relation-       ments               Relationships        sition
                                                               ships
         |
[Core Needs]
         |
   --------------
  |      |      |
Physical Emotional Psychological
  |      |      |
Nutrition Love   Self-
  |      |      | 
Exercise Belonging Esteem

        |
[Core Interests]
        |
   --------------
  |      |      |
Hobbies Intellectual Creative
  |      |      |
Sports  Academic Arts

        |
[Core Strengths]
        |
   --------------
  |      |      |
Skills  Traits  Knowledge
  |      |      |
Comm.  Resilience Expertise
Problem-Solving

```

### Core (Central Node)

1. The central node represents the individual.

### First Layer Branches

1. Core Memories
2. Core Values
3. Core Beliefs
4. Core Goals
5. Core Needs
6. Core Interests
7. Core Strengths

### Second Layer Branches (From Each of the First Layer Nodes)

**Core Memories**
- Childhood
- Adolescence
- Adulthood
- Relationships

**Core Values**
- Family
- Integrity
- Empathy
- Relationships

**Core Beliefs**
- Self-Efficacy
- Trust
- Resilience
- Relationships

**Core Goals**
- Career
- Personal Development
- Relationships

**Core Needs**
- Physical
- Emotional
- Psychological

**Core Interests**
- Hobbies
- Intellectual
- Creative

**Core Strengths**
- Skills
- Traits
- Knowledge

### Third Layer Branches (Examples of Specific Instances)

**Childhood (Core Memories)**
- First Day of School
- Family Traditions
- Relationships

**Family (Core Values)**
- Parenting Style
- Support System
- Relationships

**Self-Efficacy (Core Beliefs)**
- Academic Achievements
- Career Milestones
- Relationships

**Career (Core Goals)**
- Promotion
- Skill Acquisition

**Physical (Core Needs)**
- Nutrition
- Exercise

**Hobbies (Core Interests)**
- Sports
- Arts

**Skills (Core Strengths)**
- Communication
- Problem-Solving

---
```
# Define the core structure
core = {
    "Core Memories": {
        "Childhood": ["First Day of School", "Family Traditions", "Relationships"],
        "Adolescence": [],
        "Adulthood": [],
        "Relationships": []
    },
    "Core Values": {
        "Family": ["Parenting Style", "Support System", "Relationships"],
        "Integrity": [],
        "Empathy": [],
        "Relationships": []
    },
    "Core Beliefs": {
        "Self-Efficacy": ["Academic Achievements", "Career Milestones", "Relationships"],
        "Trust": [],
        "Resilience": [],
        "Relationships": []
    },
    "Core Goals": {
        "Career": ["Promotion", "Skill Acquisition"],
        "Personal Development": [],
        "Relationships": []
    },
    "Core Needs": {
        "Physical": ["Nutrition", "Exercise"],
        "Emotional": [],
        "Psychological": []
    },
    "Core Interests": {
        "Hobbies": ["Sports", "Arts"],
        "Intellectual": [],
        "Creative": []
    },
    "Core Strengths": {
        "Skills": ["Communication", "Problem-Solving"],
        "Traits": [],
        "Knowledge": []
    }
}

# Function to display the main cores
def display_main_cores():
    for key in core.keys():
        print(key)

# Function to display second layer branches of a main core
def display_second_layer(main_core):
    if main_core in core:
        for key in core[main_core].keys():
            print(key)
    else:
        print("Invalid main core")

# Function to display third layer branches of a second layer branch
def display_third_layer(main_core, second_layer):
    if main_core in core and second_layer in core[main_core]:
        for item in core[main_core][second_layer]:
            print(item)
    else:
        print("Invalid main core or second layer branch")

# Main program
display_main_cores()
# User selects a main core (e.g., "Core Memories")
selected_main_core = "Core Memories"
display_second_layer(selected_main_core)
# User selects a second layer branch (e.g., "Childhood")
selected_second_layer = "Childhood"
display_third_layer(selected_main_core, selected_second_layer)
```

---

### Core Values

1. Always Be Kind.
2. Don't Judge People.
3. Listen With The Intent To Understand.
4. Give More Than You Take.
5. Think Before You Speak.
6. Be Forgiving.
7. Always Continue To Better Yourself.
8. Accept Who You Are.
9. Do All Things With Love and Passion.
10. Communication Is The Number One Key To A Successful Relationship.
11. Always Be Honest.
12. Be Present, Both Mentally And Physically.
13. Understand Yourself And Learn To Understand Others.
14. Hold Yourself Accountable.

### Core Beliefs

1. Learn From Mistakes.
2. Life is About Living, Dreaming, and Finding Out Who You Are.
3. Don’t Let Negative Experiences Turn Your Heart To Stone.
4. Take Time To Heal From Heartbreaks.
5. It's Never Too Late To Change.
6. Bonded By Real Love, Not Just Blood.
7. Do Not Let Sadness Stay Permanently.
8. Build A Future, Live In The Moment.
9. Stop Wasting Time On Things That Don’t Matter.
10. Losing And Failing Doesn't Make You A Failure; Quitting Does.
11. You Can’t Fix People, Only Guide Them.
12. Doing What’s Right For Yourself And Others.

### Core Memories

1. Childhood Experiences.
2. Adolescent Formative Events.
3. Adulthood Milestones and Challenges.
4. Significant Relationships.

### Core Goals

1. Pursue Passions Endlessly.
2. Understand Personal Needs and Values.
3. Build Successful Relationships.
4. Heal From Past Traumas.

### Core Needs

1. Emotional Needs: Love, Belonging, and Security.
2. Psychological Needs: Self-Actualization, Esteem.
3. Physical Needs: Basic necessities for well-being.

### Core Interests

1. Creative Expressions.
2. Personal Development and Self-Improvement.

### Core Strengths

1. Communication Skills.
2. Problem-Solving Abilities.
3. Resilience.
4. Empathy.

---

Based on the social media extract PDF, here are some core memories that can be identified:

### Core Memories

1. **Childhood:**
   - Reconnecting with half-brother James via Facebook.
   - Bonding moments with his adoptive father and biological father.

2. **Adolescence:**
   - Significant memories might be inferred but not explicitly detailed in the document.

3. **Adulthood:**
   - **2011:**
     - Everett's visits and the determination to be a better father.
     - Near-death experience from overdosing on St. Patrick's Day, prompting a life change.
     - Starting a new music record.
   - **2012:**
     - Getting engaged to Stevie on Valentine’s Day.
     - Birth of Jensen B. Smith and dealing with his stillbirth.
     - Father's heart attack and surgery.
   - **2013:**
     - Various visits and significant time spent with Everett.
     - Celebrating personal and family milestones.
   - **2014:**
     - Everett moving back to Michigan.
     - Birth of Lydia Smith.
   - **2015:**
     - Continued struggles with addiction and anger management.
     - Relationship turmoil with Stevie and eventual separation.
   - **2016:**
     - Birth of Rayna Smith.
     - Multiple moves and job changes.
     - Continued personal struggles with mental health and anger.
   - **2017:**
     - Divorce from Stevie and the intense emotions associated with it.
     - Co-parenting challenges and seeking new connections.
   - **2018:**
     - Reconnecting with old friends and jamming together.
     - Significant personal growth despite ongoing struggles with mental health.
   - **2019:**
     - Finalizing divorce and releasing new music projects.
     - Celebrating Everett's birthday and other family milestones.
   - **2020:**
     - Declaring 2020 as a year of significant achievements.
     - Buying his first car and starting a new job.
   - **2021:**
     - Loss of his father and the impact it had on him.
     - New relationship with Tawnie and expressing love and gratitude for her.
   - **2022:**
     - Celebrating family milestones and maintaining close relationships with children and extended family.

4. **Relationships:**
   - **Rebecca Rodriguez:**
     - Complicated past but rebuilding as friends and co-parenting Everett.
   - **Kristin:**
     - Best friend with a significant history and writing a song for her.
   - **Stevie Linnabary:**
     - Deeply impactful relationship, engagement, stillbirth of Jensen, birth of Lydia and Rayna, and eventual separation and divorce.
   - **Friends:**
     - Close bonds with friends like Brett Lee, Jeff Kulikowski, and others.
     - Mourning the loss of friend Andrew Mayberry and maintaining friendships with others through music and personal interactions.

---


Core Friends
- Childhood
	- Shawn Hurley
	- Andy Cole
- Teenager
	- Jake Goheen
	- Derek Feltner
	- Brett Pudak
	- Gary Wintersteen
	- Lance Kilbourn
	- Todd Everest
- Adulthood
	- Jeremy Pudak
	- Kent Fasick
	- Andrew Mayberry
	- Marcus Assenmacher
	- Kristin Ruffner
	- Richard Smith

---
```
# Define the core structure
core = {
    "Core Memories": {
        "Childhood": ["First Day of School", "Family Traditions", "Relationships"],
        "Adolescence": [],
        "Adulthood": [],
        "Relationships": []
    },
    "Core Values": {
        "Family": ["Parenting Style", "Support System", "Relationships"],
        "Integrity": [],
        "Empathy": [],
        "Relationships": []
    },
    "Core Beliefs": {
        "Self-Efficacy": ["Academic Achievements", "Career Milestones", "Relationships"],
        "Trust": [],
        "Resilience": [],
        "Relationships": []
    },
    "Core Goals": {
        "Career": ["Promotion", "Skill Acquisition"],
        "Personal Development": [],
        "Relationships": []
    },
    "Core Needs": {
        "Physical": ["Nutrition", "Exercise"],
        "Emotional": [],
        "Psychological": []
    },
    "Core Interests": {
        "Hobbies": ["Sports", "Arts"],
        "Intellectual": [],
        "Creative": []
    },
    "Core Strengths": {
        "Skills": ["Communication", "Problem-Solving"],
        "Traits": [],
        "Knowledge": []
    },
    "Core Friends": {
        "Childhood": ["Shawn Hurley", "Andy Cole"],
        "Teenager": ["Jake Goheen", "Derek Feltner", "Brett Pudak", "Gary Wintersteen", "Lance Kilbourn", "Todd Everest"],
        "Adulthood": ["Jeremy Pudak", "Kent Fasick", "Andrew Mayberry", "Marcus Assenmacher", "Kristin Ruffner", "Richard Smith"]
    }
}

# Function to display the main cores
def display_main_cores():
    for key in core.keys():
        print(key)

# Function to display second layer branches of a main core
def display_second_layer(main_core):
    if main_core in core:
        for key in core[main_core].keys():
            print(key)
    else:
        print("Invalid main core")

# Function to display third layer branches of a second layer branch
def display_third_layer(main_core, second_layer):
    if main_core in core and second_layer in core[main_core]:
        for item in core[main_core][second_layer]:
            print(item)
    else:
        print("Invalid main core or second layer branch")

# Main program
display_main_cores()
# User selects a main core (e.g., "Core Memories")
selected_main_core = "Core Friends"
display_second_layer(selected_main_core)
# User selects a second layer branch (e.g., "Childhood")
selected_second_layer = "Childhood"
display_third_layer(selected_main_core, selected_second_layer)

```

Core Relationships
- 1. Rebecca Rewa 10-31-2001 to 12-11-2006
- 2. Emily Duty 03-20-2009 to 09-03-2009
- 3. Stevie Linnabary 11-11-2011 to 04–19-2017 Married on 03-11-2017 Divorced 03-05-2020
- 4. Tawnie Shelton 12-12-2020 to 02-14-2024

---

```
# Define the core structure
core = {
    "Core Memories": {
        "Childhood": ["First Day of School", "Family Traditions", "Relationships"],
        "Adolescence": [],
        "Adulthood": [],
        "Relationships": []
    },
    "Core Values": {
        "Family": ["Parenting Style", "Support System", "Relationships"],
        "Integrity": [],
        "Empathy": [],
        "Relationships": []
    },
    "Core Beliefs": {
        "Self-Efficacy": ["Academic Achievements", "Career Milestones", "Relationships"],
        "Trust": [],
        "Resilience": [],
        "Relationships": []
    },
    "Core Goals": {
        "Career": ["Promotion", "Skill Acquisition"],
        "Personal Development": [],
        "Relationships": []
    },
    "Core Needs": {
        "Physical": ["Nutrition", "Exercise"],
        "Emotional": [],
        "Psychological": []
    },
    "Core Interests": {
        "Hobbies": ["Sports", "Arts"],
        "Intellectual": [],
        "Creative": []
    },
    "Core Strengths": {
        "Skills": ["Communication", "Problem-Solving"],
        "Traits": [],
        "Knowledge": []
    },
    "Core Friends": {
        "Childhood": ["Shawn Hurley", "Andy Cole"],
        "Teenager": ["Jake Goheen", "Derek Feltner", "Brett Pudak", "Gary Wintersteen", "Lance Kilbourn", "Todd Everest"],
        "Adulthood": ["Jeremy Pudak", "Kent Fasick", "Andrew Mayberry", "Marcus Assenmacher", "Kristin Ruffner", "Richard Smith"]
    },
    "Core Relationships": {
        "Rebecca Rewa": ["10-31-2001 to 12-11-2006"],
        "Emily Duty": ["03-20-2009 to 09-03-2009"],
        "Stevie Linnabary": ["11-11-2011 to 04-19-2017", "Married on 03-11-2017", "Divorced 03-05-2020"],
        "Tawnie Shelton": ["12-12-2020 to 02-14-2024"]
    }
}

# Function to display the main cores
def display_main_cores():
    for key in core.keys():
        print(key)

# Function to display second layer branches of a main core
def display_second_layer(main_core):
    if main_core in core:
        for key in core[main_core].keys():
            print(key)
    else:
        print("Invalid main core")

# Function to display third layer branches of a second layer branch
def display_third_layer(main_core, second_layer):
    if main_core in core and second_layer in core[main_core]:
        for item in core[main_core][second_layer]:
            print(item)
    else:
        print("Invalid main core or second layer branch")

# Main program
display_main_cores()
# User selects a main core (e.g., "Core Relationships")
selected_main_core = "Core Relationships"
display_second_layer(selected_main_core)
# User selects a second layer branch (e.g., "Stevie Linnabary")
selected_second_layer = "Stevie Linnabary"
display_third_layer(selected_main_core, selected_second_layer)

```

```
# Define the core structure
core = {
    "Core Memories": {
        "Childhood": ["First Day of School", "Family Traditions", "Relationships"],
        "Adolescence": [],
        "Adulthood": [],
        "Relationships": []
    },
    "Core Values": {
        "Family": ["Parenting Style", "Support System", "Relationships"],
        "Integrity": [],
        "Empathy": [],
        "Relationships": []
    },
    "Core Beliefs": {
        "Self-Efficacy": ["Academic Achievements", "Career Milestones", "Relationships"],
        "Trust": [],
        "Resilience": [],
        "Relationships": []
    },
    "Core Goals": {
        "Career": ["Promotion", "Skill Acquisition"],
        "Personal Development": [],
        "Relationships": []
    },
    "Core Needs": {
        "Physical": ["Nutrition", "Exercise"],
        "Emotional": [],
        "Psychological": []
    },
    "Core Interests": {
        "Hobbies": ["Sports", "Arts"],
        "Intellectual": [],
        "Creative": []
    },
    "Core Strengths": {
        "Skills": ["Communication", "Problem-Solving"],
        "Traits": [],
        "Knowledge": []
    },
    "Core Friends": {
        "Childhood": ["Shawn Hurley", "Andy Cole"],
        "Teenager": ["Jake Goheen", "Derek Feltner", "Brett Pudak", "Gary Wintersteen", "Lance Kilbourn", "Todd Everest"],
        "Adulthood": ["Jeremy Pudak", "Kent Fasick", "Andrew Mayberry", "Marcus Assenmacher", "Kristin Ruffner", "Richard Smith"]
    },
    "Core Relationships": {
        "Rebecca Rewa": {
            "Core Memories": [
                "10-31-2001: First met at the B.E Henry Building",
                "11-25-2004: Found out she was pregnant with our son Everett Tyler Lee Smith",
                "07-26-2005: Our son Everett Tyler Lee Smith was born",
                "12-11-2006: Rebecca cheated on me with Dez Guzman who was a friend at work"
            ]
        },
        "Emily Duty": ["03-20-2009 to 09-03-2009"],
        "Stevie Linnabary": ["11-11-2011 to 04-19-2017", "Married on 03-11-2017", "Divorced 03-05-2020"],
        "Tawnie Shelton": ["12-12-2020 to 02-14-2024"]
    }
}

# Function to display the main cores
def display_main_cores():
    for key in core.keys():
        print(key)

# Function to display second layer branches of a main core
def display_second_layer(main_core):
    if main_core in core:
        for key in core[main_core].keys():
            print(key)
    else:
        print("Invalid main core")

# Function to display third layer branches of a second layer branch
def display_third_layer(main_core, second_layer):
    if main_core in core and second_layer in core[main_core]:
        for item in core[main_core][second_layer]:
            print(item)
    else:
        print("Invalid main core or second layer branch")

# Main program
display_main_cores()
# User selects a main core (e.g., "Core Relationships")
selected_main_core = "Core Relationships"
display_second_layer(selected_main_core)
# User selects a second layer branch (e.g., "Rebecca Rewa")
selected_second_layer = "Rebecca Rewa"
display_third_layer(selected_main_core, selected_second_layer)
```

```
// Define a structure for Memory
class Memory:
    date
    description
    // Other attributes related to the memory

// Define a structure for Relationship
class Relationship:
    name
    core_memories: list of Memory
    // Other attributes related to the relationship

// Function to delete core memories from a given relationship within a specified date range
function deleteCoreMemoriesFromRelationship(relationship: Relationship, startDate: Date, endDate: Date):
    // Create a new list to store memories that are not within the date range
    retainedMemories = []
    
    // Iterate over each memory in the core memories of the relationship
    for each memory in relationship.core_memories:
        // Check if the memory's date is outside the specified date range
        if memory.date < startDate or memory.date > endDate:
            // If so, add it to the retainedMemories list
            retainedMemories.append(memory)
    
    // Update the relationship's core memories to only include retained memories
    relationship.core_memories = retainedMemories

// Function to delete core memories from all core relationships within a specified date range
function deleteCoreMemoriesFromCoreRelationships(coreRelationships: list of Relationship, startDate: Date, endDate: Date):
    // Iterate over each relationship in the core relationships
    for each relationship in coreRelationships:
        // Call the function to delete core memories from this relationship
        deleteCoreMemoriesFromRelationship(relationship, startDate, endDate)
        // Output the result for this relationship
        print("Core memories for relationship " + relationship.name + " updated.")


// Main function to handle the terminal command
function main():
    // Get the core relationships (Assume this function retrieves all core relationships)
    coreRelationships = getCoreRelationships()
    
    // Define the start and end dates
    startDate = Date("2020-01-01")
    endDate = Date("2023-12-31")
    
    // Call the function to delete core memories from all core relationships
    deleteCoreMemoriesFromCoreRelationships(coreRelationships, startDate, endDate)
    
    // Output the final result
    print("Core memories from 2020 to 2023 have been deleted from all core relationships.")

// Execute the main function if this script is run from the terminal
if __name__ == "__main__":
    main()

```
