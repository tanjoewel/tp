[![CI Status](https://github.com/AY2122S1-CS2103-F09-1/tp/workflows/Java%20CI/badge.svg)](https://github.com/AY2122S1-CS2103-F09-1/tp/actions)

![Ui](docs/images/Ui.png)

* This is **a sample project for Software Engineering (SE) students**.<br>
  Example usages:
  * as a starting point of a course project (as opposed to writing everything from scratch)
  * as a case study
* The project simulates an ongoing software project for a desktop application (called _AddressBook_) used for managing contact details.
  * It is **written in OOP fashion**. It provides a **reasonably well-written** code base **bigger** (around 6 KLoC) than what students usually write in beginner-level SE modules, without being overwhelmingly big.
  * It comes with a **reasonable level of user and developer documentation**.
* It is named `AddressBook Level 3` (`AB3` for short) because it was initially created as a part of a series of `AddressBook` projects (`Level 1`, `Level 2`, `Level 3` ...).
* For the detailed documentation of this project, see the **[Address Book Product Website](https://se-education.org/addressbook-level3)**.
* This project is a **part of the se-education.org** initiative. If you would like to contribute code to this project, see [se-education.org](https://se-education.org#https://se-education.org/#contributing) for more info.


## Features

### Module

#### Module add

* Create a new module
* Format: `module add <module name>`

#### Module add task

* Create a new task for a specific module
* Format: `module add <module name>, <task name>`

#### Module add student

* Add a student to a specific module
* Format: `module add <module name>, <student id>`

#### Module delete student

* Delete a student from a specific module
* Format: `module delete <module name>, <student id>`

#### Module delete

* Delete a module
* Format: `module delete <module name>`


### Task

#### Task done

* Mark a student’s task as complete
* Format: `task done <module name>, <task name>, <student id>`

#### Task undone

* Mark a student’s task as incomplete
* Format: `task undone <module name>, <task name>, <student id>`


### Student

#### Student get

* Retrieve a student's information
* Format: `student get <student id>`


## Acknowledgement

This project is based on the AddressBook-Level3 project created by the [SE-EDU initiative](https://se-education.org).
