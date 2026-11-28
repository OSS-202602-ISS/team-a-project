# Project Plan

Required deliverable, written in Chapter 11 and updated as things change.
Keep it to this one page.

In Chapter 11, copy your team's `[Team plan]` issue (in `practice-pr`) into
this file:

| `[Team plan]` issue | This file |
|---|---|
| Topic | 1. The tool - One sentence |
| Track | 1. The tool - Track |
| Input / Process / Output | 2. Scope |
| Libraries (whitelist only) | 3. Open source we plan to use |
| Roles | 4. Team and roles |

## 1. The tool

- **Name**: Lost and Found Tracker
- **One sentence**: A tool that helps students find lost items by showing a list of items that have not been collected.
- **Category**: data processing
- **Track**: A only

## 2. Scope - input, one processing step, output

| | Our project |
|---|---|
| **Input** | lost_items.csv (item name, location, date, status) |
| **Processing step** | Read the CSV file and find items that have not been collected |
| **Output** | A list of uncollected items shown on the screen |

**Definition of done**: one run command, one input, one output result.
Anything beyond that is track B, not the baseline.

## 3. Open source we plan to use

| Library | Why we need it | On the whitelist? |
|---|---|---|
| pandas | reads and filters lost_items.csv | yes |
| rich | shows the results clearly on the screen | yes |

One row for each library. For example: `| pandas | reads servers.csv | yes |`

Libraries not covered in class have a recipe card - read it before you add one.

## 4. Team and roles

Write GitHub usernames (for example @gildong-hong). In a team of two or three,
one person can take two roles. Roles can rotate later. If roles change, update
this table.

| Role | Who |
|---|---|
| PM | @crisdinatamang123-del |
| Developer | @rekha2059 |
| Documentation | @rekha2059 |
| Reviewer | @rekha2059 |

## 5. Schedule

| Chapter | What we finish |
|---|---|
| 11 | Repository set up, plan written, 3 issues opened, first feature branch |
| 12 | Core feature works end to end (the two blanks are filled) |
| 13 | Peer review, error handling, documentation complete, tests pass |
| Final submission | Final tag, "My contribution" written, peer evaluation done |

## 6. Risks

| What could go wrong | What we will do about it |
|---|---|
| \<e.g. our input file has empty cells or extra columns\> | \<e.g. shrink to one column and validate it\> |
