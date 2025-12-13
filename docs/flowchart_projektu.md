```mermaid
flowchart TD
    Start([Start])
    Load[Load tasks from tasks.txt]
    Menu[Display menu to the user]
    Read[Read user choice]
    Valid{Is choice valid?}

    Action[Execute selected action]
    Error[Show error message and return to menu]

    Save[Save tasks to tasks.txt]
    ExitCheck{Did user choose Exit?}
    End([End])

    Start --> Load
    Load --> Menu
    Menu --> Read
    Read --> Valid

    Valid -- Yes --> Action
    Valid -- No --> Error
    Error --> Menu

    Action --> Save
    Save --> ExitCheck

    ExitCheck -- Yes --> End
    ExitCheck -- No --> Menu
