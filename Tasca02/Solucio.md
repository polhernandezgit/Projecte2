# Informe tècnic: Selecció d'un SAI per una empresa client

**Autor:** Pol Hernández\
**Curs:** Sistemes microinformàtics i xarxes 2B - Seguretat informàtica\
**Enllaç:** [Google
Drive](https://drive.google.com/drive/u/0/folders/1gxAv-g1949wPHjVZ0O2bhYzN_9W0S1a_)

------------------------------------------------------------------------

## Índex

1.  [Descripció del cas](#descripció-del-cas)
2.  [Inventari d'equips](#inventari-dequips)
3.  [Càlcul de potència total](#càlcul-de-potència-total)
4.  [Determinació de l'autonomia](#determinació-de-lautonomia)
5.  [Recerca de models de SAI](#recerca-de-models-de-sai)
6.  [Selecció d'un SAI final](#selecció-dun-sai-final)

------------------------------------------------------------------------

## Descripció del cas

L'empresa **TecnoGestió S.L.**, dedicada a la gestió documental i
assessorament informàtic, té un petit despatx amb 4 ordinadors de
sobretaula, una impressora-fotocopiadora multifunció (similar a les que
té l'escola) i un router d'accés a Internet.
Davant les constants incidències amb el subministrament elèctric a la
zona, la direcció ha decidit adquirir un **SAI (Sistema d'Alimentació
Ininterrompuda)** per garantir la continuïtat del servei i protegir els
equips.

------------------------------------------------------------------------

## Inventari d'equips

**Dispositius connectats al SAI:**
- 4 ordinadors de sobretaula
- 4 monitors
- 1 router d'accés a Internet

> La impressora-fotocopiadora multifunció **no es connectarà** al SAI,
> ja que pot sobrecarregar-lo i no és essencial per al rendiment del
> treball.

**Consum estimat per dispositiu:** - Ordinador: 580 W\
- Monitor: 30 W\
- Router: 20 W

**Total de consum:**

    Ordinadors: 580 × 4 = 2320 W  
    Monitors: 30 × 4 = 120 W  
    Router: 20 W  
    **Total: 2460 W**

------------------------------------------------------------------------

## Càlcul de potència total

**Potència aparent:**

    Potència aparent = 2460 / 0,7 = 3514 VA

**Amb reserva del 20%:**

    3514 / 0,8 = 4392 VA

------------------------------------------------------------------------

## Determinació de l'autonomia

S'estima que el SAI ha de mantenir els equips funcionant almenys **10
minuts**, per permetre guardar treballs i apagar correctament.

Tenint en compte la càrrega activa de **2460 W**, un SAI d'uns **5 kVA**
pot proporcionar entre **10 i 30 minuts d'autonomia**.
El càlcul exacte de la capacitat de la bateria és:

    (T * Pot / E) / 60 = (10 * 4392 / 0,9) / 60 = 813 Ah

Per tant, per un temps de 10 minuts, es necessita una bateria
d'aproximadament **813 Ah**.

------------------------------------------------------------------------

## Recerca de models de SAI

**- Cerca de 2 o 3 models de SAI que compleixin els requisits:**
Els SAI que recomano son els següents:


  -------------------------------------------------------------------------------
| Característiques                | **SLC-4000-TWIN PRO3** | **SLC-4000-TWIN RT3** | **SLC-7,5-CUBE4** |
|--------------------------------|------------------------|-----------------------|-------------------|
| **Potència (VA)**              | 4000 VA               | 4000 VA              | 7500 VA           |
| **Topologia**                  | Online, doble conversió | Online, doble conversió | Online, doble conversió, DSP control |
| **Freqüència d’entrada**       | 50 / 60 Hz            | 50 / 60 Hz (segons potència) | 50 / 60 Hz (segons potència) |
| **Eficiència (mode online)**   | 95%                   | 95%                  | 95% - 98%         |
| **Eficiència (mode ECO)**      | 98%                   | 98%                  | 98%               |
| **Dimensions (A×P×H)**         | 225×492×589 mm        | 439×592×129 mm       | 250×689×827 mm    |
| **Pes**                        | 51 kg                 | 55,6 kg              | 88 kg             |
| **Sortides**                   | 8 × IEC C13           | 8 × IEC C13          | Bornes trifàsiques per càrregues industrials |
| **Preu aproximat**             | 1.750 € - 2.200 €     | 2.000 € - 2.350 €    | 4.598 €           |
| **Marca**                      | Salicru               | Salicru              | Salicru           |


------------------------------------------------------------------------

## Selecció d'un SAI final

El **SAI recomanat** per a l'empresa **TecnoGestió S.L.** és el model
**Salicru SLC-4000-TWIN PRO3**, ja que ofereix una bona relació entre
**rendiment, eficiència, possibilitats d'expansió de la bateria** i
**dimensions compactes**, fent-lo ideal per a les necessitats del
client.
