# PROJETO-4-MODELAGEM-DE-UM-PEQUENO-SISTEMA-COM-UML-E-BPMN

-------------------------------------SISTEMA DE REESERVA DE SALAS-------------------------------------------

DUPLA: Sophia e Lauriene

  Reserva --|> Sala : reserva
  Reserva --|> Usuário : reserva
  
  class Sala {
    +id: int
    +nome: string
    +capacidade: int
  }
  
  class Usuário {
    +id: int
    
    +nome: string
    
    +email: string
  }
  
  class Reserva {
    +id: int
    +data: Date
    +horaInicio: Time
    +horaFim: Time
  }

