class Integrante_IFRN:
  def __init__(self, nome_ifrn):
      self.nome_ifrn = nome_ifrn

  def exibirMensagem(self):
      print("Seja bem-vindo(a) ao IFRN!!!")

  def nome(self):
      print("Olá eu sou o Instituto Federal- IFRN")

class Professor(Integrante_IFRN):
  def __init__(self, nome_ifrn, materia ):
      super().__init__(nome_ifrn)
      self.materia = ministra

  def materia_aula(self):
      print(f"minha aula é de {self.ministra}")

  def exibirMensagem(self):
      print("Meus alunos são os melhores!!!")

class Aluno(Integrante_IFRN):
  def __init__(self, nome_ifrn, curso):
      super().__init__(nome_ifrn)
      self.curso = curso

  def estudo(self):
      print(f"Faço curso de {self.curso}")

  def exibirMensagem(self):
      print("Vou estudar pra tirar 100 em POO!!!")

integrante = Integrante_IFRN("IFRN")
professor = Professor("IFRN", "Programação")
aluno = Aluno("IFRN", "Faço informatica")

integrante.exibirMensagem()
integrante.nome()
professor.exibirMensagem()
professor.ministra_aula()
aluno.exibirMensagem()
aluno.estudo()
#finalizado

