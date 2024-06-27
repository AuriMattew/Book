
### User Requirements Specification Document
##### DIBRIS – Università di Genova. Scuola Politecnica, Software Engineering Course 80154


**VERSION : 1.0**

**Authors**  
Aurino
Matteo

**REVISION HISTORY**

| Version    | Date        | Authors      | Notes        |
| 1.0 | 18/06/2024 | Aurino Matteo | added png pic! |
| X.X |  | |  |

# Table of Contents

1. [Introduction](#p1)
	1. [Document Scope](#sp1.1)
	2. [Definitios and Acronym](#sp1.2) 
	3. [References](#sp1.3)
2. [System Description](#p2)
	1. [Context and Motivation](#sp2.1)
	2. [Project Objectives](#sp2.2)
3. [Requirement](#p3)
 	1. [Stakeholders](#sp3.1)
 	2. [Functional Requirements](#sp3.2)
 	3. [Non-Functional Requirements](#sp3.3)
  
  

<a name="p1"></a>

## 1. Introduction

<a name="sp1.1"></a>

### 1.1 Document Scope


<a name="sp1.2"></a>

### 1.2 Definitios and Acronym


| Acronym				| Definition | 
| ------------------------------------- | ----------- | 
| XXXX                                  | XXXX |

<a name="sp1.3"></a>

### 1.3 References 

<a name="p2"></a>

## 2. System Description
<a name="sp2.15"></a>

### 2.1 Context and Motivation

<a name="sp2.2"></a>

### 2.2 Project Obectives 

<a name="p3"></a>

## 3. Requirements

| Priorità | Significato | 
| --------------- | ----------- | 
| M | **Mandatory:**   |
| D | **Desiderable:** |
| O | **Optional:**    |
| E | **future Enhancement:** |

<a name="sp3.1"></a>
### 3.1 Stakeholders

<a name="sp3.2"></a>
### 3.2 Functional Requirements 

| ID | Descrizione | Priorità |
| --------------- | ----------- | ---------- | 
| 1.0 |  XXXXX |M|

<a name="sp3.3"></a>
### 3.2 Non-Functional Requirements 
 
| ID | Descrizione | Priorità |
| --------------- | ----------- | ---------- | 
| 1.0 | XXXXX |M|

**# ATTORI**

1) cliente : esegue richieste di operazione sui suoi conti correnti
2) banca : esegue controlli in relazione alle azioni che può compiere il cliente della banca
3) operatore : addetto al funzionamento fisico della macchina, accende o spegne.

#CLIENTE :


casi d'uso = 

1)richiesta prelievo

2)richiesta saldo

3)richiesta trasferimento

4)richiesta accredito


#OPERATORE : 


casi d'uso =

1)accensione

2)spegnimento


**Scenario Principale**

1) cliente inserisce carta

2) cliente inserisce PIN corretto

3) cliente seleziona azione da compiere

4) cliente seleziona quantità di denaro

5) cliente ritira l'erogazione della tessera/ricevuta/soldi

6) macchina pulisce schermo e torna alla schermata iniziale




**Scenario Alternativo A**

1.A) ATM notifica che il PIN e' errato per la terza volta
		
     1.A) ATM notifica che il PIN inserito è scorretto.

     1.A) ATM notifica che non restituira' la tessera.

     1.A) ATM va al punto 6 dello scenario principale


**Scenario Alternativo B**

     1.B) ATM notifica che il Pin è corretto ed invita a reinserirlo
     1.B) 




![Ciao!](imgs/atm.png)

