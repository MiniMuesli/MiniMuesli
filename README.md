erDiagram
    Citizen ||--o{ Cita : "Solicita"
    Cita }--o|| Centro_de_Salud : "Realizada en"
    Centro_de_Salud }--o{ Citizen : "Asociado a"
    Centro_de_Salud }--o|{ Cita : "Programada"

