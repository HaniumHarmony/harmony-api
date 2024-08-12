# GitHub Role
This repository follows the following conventions.

## Commit Convention

| Commit Type | Description                                                                |
| ----------- | -------------------------------------------------------------------------- |
| feat        | Add new features                                                           |
| fix         | Fix bugs                                                                   |
| docs        | Modify documentation                                                       |
| style       | Code formatting, missing semicolons, no changes to the code itself         |
| refactor    | Code refactoring                                                           |
| test        | Add test code, refactor test code                                          |
| chore       | Modify package manager, and other miscellaneous changes (e.g., .gitignore) |
| design      | Change user UI design, such as CSS                                         |
| comment     | Add or modify necessary comments                                           |
| rename      | Only changes to file or folder names or locations                          |
| remove      | Only performing the action of deleting files                               |

## PR Convention

| Icon | Code                       | Description                       |
| ---- | -------------------------- | --------------------------------- |
| 🧑🏻‍🎨   | :art                       | Improve code structure/formatting |
| ⚡️  | :zap                       | Performance improvement           |
| 🔥   | :fire                      | Delete code/files                 |
| 🐛   | :bug                       | Fix bugs                          |
| 🚑   | :ambulance                 | Urgent fixes                      |
| ✨   | :sparkles                  | Introduce new features            |
| 💄   | :lipstick                  | Add/modify UI/style files         |
| ⏪   | :rewind                    | Revert changes                    |
| 🔀   | :twisted_rightwards_arrows | Merge branches                    |
| 💡   | :bulb                      | Add/modify comments               |
| 🗃    | :card_file_box             | Database-related changes          |

# Project Role

## Project Structure
```
📦 all_project/		# (1) repositroy_root	
├─ .gitignore
├─ README.md
├─ requirements.txt
├─ myvenv/
└─ my_project/		# (2) project_root	
   ├─ .env 	
   ├─ app/
   │  ├─ models/
   │  │  └─ __init__.py
   │  │  └─ profile.py
   │  │  └─ instagram.py
   │  ├─ admin.py
   │  ├─ models.py
   │  ├─ tests.py
   │  ├─ views/
   │  └─ forms/
   ├─ config/		# (3) configuration_root
   │  ├─ settings/
   │  │  └─ settings.py
   │  ├─ __init__.py
   │  ├─ asgi.py
   │  ├─ urls.py
   │  └─ wsgi.py
   ├─ static/
   │  └─ myapp/
   ├─ media/
   │  └─ myapp/
   ├─ templates/	
   │  └─ myapp/
   └─ manage.py
```
🤔 참고 출처: https://velog.io/@duo22088/Django-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EA%B5%AC%EC%A1%B0