RCOMP 2020-2021 Project - Sprint 1 - Member 1191045 folder
===========================================

# Edifício 4

A representação do Edifício 4 pode ser visualizada nas seguintes imagens. Inclui a localização dos cabos de cobre e de fibra, cross-connects, access-points, consolidation points e das fichas.

![Floor0](/doc/sprint1/1191045/FigurasAux/GroundFloor.png)

![Floor1](/doc/sprint1/1191045/FigurasAux/UpperFloor.png)

Há cabos que estão nas paredes e também cabos numa calha suspensa representada a verde. Deve ainda ser referido que as fichas mais perto das paredes são fichas de parede e os cabos situados na respetiva parede ligam-se a elas. Os APs do piso 0 estão situados na calha suspensa, e o AP do piso 1 está localizado no teto da respetiva divisão.

## Áreas:

#### Piso 0:

40.1: 54,42 metros quadrados (12 tomadas).

40.2: 54,42 metros quadrados (12 tomadas).

40.3: 58,05 metros quadrados (12 tomadas).

40.4: 47,17 metros quadrados (10 tomadas).

Área Aberta: 1 710,20 metros quadrados (344 tomadas).

#### Piso 1:

41.1: 54,42 metros quadrados (12 tomadas).

41.2: 54,42 metros quadrados (12 tomadas).

41.3: 93,88 metros quadrados (20 tomadas).

41.4: 36,28 metros quadrados (8 tomadas).

Área Aberta: 1 710,20 metros quadrados.

## Tipo de cabos utilizados e os caminhos por eles percorridos

No interior dos edifícios a utilização de fios de cobre (CAT7) será valorizada e adotada na planificação deste edifício (desde que sejam inferiores a 90 metros). A conexão entre ligações entre bastidores (IC,HC,CP) vai ser valorizado a ligação por cabos de fibra, e vão ser usados 2 por ligação para evitar possíveis falhas na rede. Os APs vão ser ligados por fios de cobre (CAT7).

## Metros de cabo necessários:

### Piso 0:

#### Cobre:

40.1: 120,65 m (usando a média dos cabos).

40.2: 110,19 m (usando a média dos cabos).

40.3: 209,68 m (usando a média dos cabos).

40.4: 70,27 m (usando a média dos cabos).

Área Aberta: 5836,38 m (usando a média dos cabos).

Entre patch panels e switch: 201 m.

Total: 6548,16 m.

#### Fibra:

Total: 519,05 m (Pois todas as ligações entre bastidores são usados 2 cabos de fibra).

### Piso 1:

#### Cobre:

41.1: 120,65 m (usando a média dos cabos).

41.2: 117,65 m (usando a média dos cabos).

41.3: 334,59 m (usando a média dos cabos).

41.4: 82,43 m (usando a média dos cabos).

Entre patch panels e switch: 28 m.

Total: 683,32 m.

#### Fibra:

Total: 64,57 m (Pois todas as ligações entre bastidores são usados 2 cabos de fibra).

### Edifício 4:

#### Cobre:

Total: 7231,49 m.

#### Fibra:

Total: 583,62 m.

###### NOTA: Cálculos feitos na folha de Excel auxiliar.

## Inventário

### Piso 0

Total de tomadas: 390.

Para o HC: Patch panel do tipo CAT7 com 24 portas (1U), patch panel de fibra com 24 portas (1U), assim adicionamos um switch (1U), ficando com 3U total. Como temos de ter 50% de espaço livre, teria de ser colocado um HC com capacidade para 6U.

Para o IC: IC localizado perto do HC.

Para o CP: 5 CPs. O localizado na sala 40.2 tem patch panel do tipo CAT7 com 48 portas (2U), assim adicionamos um switch (1U), ficando com 3U total. Como temos de ter 50% de espaço livre, teria de ser colocado um CP com capacidade para 6U. Os localizados na sala aberta têm patch panels do tipo CAT7 com 96 portas (4U), sendo 86 delas usadas, assim adicionamos switch (2U), ficando com 6U total. Como temos de ter 50% de espaço livre, teriam de ser colocados CPs com capacidade para 12U.

Para o AP: 2 APs, com os canais 11 (localizado mais há esquerda) e 6 (localizado mais há direita) de 2,4GHz, estando ambos na calha suspensa.

### Piso 1

Total de tomadas: 52.

Para o HC: Patch panel do tipo CAT7 com 48 portas (2U), patch panel de fibra com 24 portas (1U), assim adicionamos dois switchs (2U), ficando com 5U total. Como temos de ter 50% de espaço livre, teria de ser colocado um HC com capacidade para 10U.

Para o CP: Patch panel do tipo CAT7 com 48 portas (2U), assim adicionamos um switch (1U), ficando com 3U total. Como temos de ter 50% de espaço livre, teria de ser colocado um CP com capacidade para 6U.

Para o AP: 1 AP, com os canal 1 de 2,4GHz, localizado no teto da divisão.

###### NOTA: Ambos CPs e todos os HCs têm pelo menos duas entradas para cabos de fibra nos switchs.
