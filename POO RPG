class Personagem:

    vida = 150
    mana = 100
    inteligencia = 30
    forca = 30
    agilidade = 30
    carisma = 20

    def __init__(self,nome):
        self.nome = nome

    def atacar(self,inimigo):
        inimigo.vida -= self.forca
        print(f'{self.nome} tirou {self.forca} pontos de vida de {inimigo.nome}')


class Guerreiro(Personagem):

    vida = 200
    inteligencia = 10
    agilidade = 20

    def esmagar(self,inimigo):
        inimigo.vida -= self.forca*2
        print(f'{self.nome} ESMAGOU {inimigo.nome} tirando {2*self.forca} pontos de vida.')

class Mago(Personagem):
    inteligencia = 80
    forca = 10
    agilidade = 20

    def magia(self,inimigo):
        inimigo.vida -= self.inteligencia*2
        print(f'{self.nome} lançou uma bola de fogo em {inimigo.nome} tirando {2*self.inteligencia} pontos de vida.')

class Bardo(Personagem):
    carisma = 70
    forca = 10
    agilidade = 20

    def curar(self,aliado):
        aliado.vida += self.carisma*2
        print(f'{self.nome} restaurou {self.carisma*2} pontos de vida de {aliado.nome}.')

class Arqueiro(Personagem):
    agilidade = 80
    forca = 20
    inteligencia = 20
    carisma = 10

    def flechar(self,inimigo):
        inimigo.vida -= self.agilidade*2
        print(f'{self.nome} lançou uma flecha em {inimigo.nome} tirando {self.agilidade*2} pontos de vida.')

g1 = Guerreiro("Darius")
m1 = Mago("Gandalf")
b1 = Bardo("Miguel")
a1 = Arqueiro("Legolas")

a1.flechar(g1)
print(f'{g1.nome} agora possui {g1.vida} pontos de vida.')
