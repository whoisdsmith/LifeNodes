# Cmd

I want to simulate a mock terminal cmd that will
do the following:

- Gain access to Core Modules and enter into the Core Relationship module and ask to select a person
- Input TS as person
- Acesss TS Core Memories Module and list memories from 2020, 2021, 2022, 2023, 2024
- Select all Memories from 2020, 2021, 2022, 2023, 2024 and purge all Memories and Person TS and return with process completed


access my Core Relationships

Access = Core Relationships -> Person -> TS

Access = Core Memories -> Dates -> All

```
$ core_modules

Welcome to Core Modules! Please choose which a Module.

1. Core_Dates
2. Core_Events
3. Core_Memories
4. Core_Relationships
5. Core_System

$ core_modules --Core_Relationships

Welcome to Core Relationships! Please choose available persons:
1. TS
2. SL
3. ED
4. RR

$ Core_Relationships --Core_People
Select person (e.g., enter 1 for TS): 1

$ Core_People TS
Person TS selected.For 

$ TS_Core_Memories --list_memories 

2020 2021 2022 2023 2024
Memories from 2020:
- [2020-03-15] Memory A
- [2020-07-04] Memory B
Memories from 2021:
- [2021-01-20] Memory C
- [2021-12-25] Memory D
Memories from 2022:
- [2022-02-14] Memory E
- [2022-11-16] Memory F
Memories from 2023:
- [2023-05-05] Memory G
- [2023-10-31] Memory H
Memories from 2024:
- [2024-02-29] Memory I
- [2024-06-30] Memory J


$ TS_Core_Memories --select_all_memories --purge_memories

Warning: This action will delete all selected memories permanently. Do you wish to continue? (yes/no): 

purge_memories yes
Deleting memories...

All memories from 2020, 2021, 2022, 2023, and 2024 deleted.

$ Core_People TS --purge_person TS
Warning: This action will delete person TS permanently. Do you wish to continue? (yes/no): 

purge_person TS yes
Deleting person TS...
Person TS deleted.

$ exit_module
Process completed.
```

```
[
  {
    "input": "simple input",
    "output": [
      "simple output"
    ]
  },
  {
    "input": "let's see some color",
    "output": [
      "<span style=\"color:#33BBC8\">Wow it's cyan</span> <span style=\"color:#ADAD27\">and yellow</span> <span style=\"color:#C23621\">and red</span> and back"
    ]
  },
  {
    "input": "try out some unicode and emojis 😍",
    "output": [
      "🔥 Nice <span style=\"color:#25BC24\">✔︎</span>"
    ]
  },
          "replace": true
      },
      {
        "content": "Complete"
      }
    ]
  },
  {
    "input": "how about some spacing?",
    "output": [
      "       left pad",
      "right pad       !",
      "the lines...<br/><br/>can break"
    ]
  },
        },
      {
        "content": "/ Loading",
        "replace": true
      },
      {
        "content": "- Loading",
        "replace": true
      },
      {
        "content": "\\ Loading",
        "replace": true
      },
      {
        "content": "| Loading",
        "replace": true
      },
      {
        "content": "/ Loading",
        "replace": true
      },
      {
        "content": "- Loading",
        "replace": true
      },
      {
        "content": "Complete"
      }
    ]
  },
   {
    "input": "how about some spacing?",
    "output": [
      "       left pad",
      "right pad       !",
      "the lines...<br/><br/>can break"
    ]
  },
  {
    "input": "it automatically tails content, with only css!",
    "output": [
      "line 1",
      "line 2",
      "line 3",
      "line 4",
      "line 5",
      "line 6",
      "line 7",
      "line 8",
      "line 9",
      "line 10",
      "Done!"
    ]
  }
]
```
