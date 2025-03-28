# PROJETO-4-MODELAGEM-DE-UM-PEQUENO-SISTEMA-COM-UML-E-BPMN

-------------------------------------SISTEMA DE REESERVA DE SALAS-------------------------------------------

DUPLA: Sophia e Lauriene

  Reserva --|> Sala : reserva
  Reserva --|> Usuário : reserva
  
  Sala {
    +id: int
    +nome: string
    +capacidade: int
  }
  
  Usuário {
    +id: int
    +nome: string
    +email: string
  }
  
  Reserva {
    +id: int
    +data: Date
    +horaInicio: Time
    +horaFim: Time
  }

