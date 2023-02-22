# TFE
réalisation d'une application web pour le département monitoring 

flowchart TD
    A[user] -->|se connecte à l'application| B(minfin)
    B --> C{toDoList}
    C -->D[listExcel]
    C -->|get api dynatrace| E[listApplication]
    
