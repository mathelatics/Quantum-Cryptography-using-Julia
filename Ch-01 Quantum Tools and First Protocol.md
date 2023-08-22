# Ch-01 Quantum Tools and First Protocol

> We already learned about the quantum information concepts like quantum states : pure, mixed states, quantum entanglement, quantum measurement, reduced states and many more. Then Here we are going to think about the question i.e What are the use of quantum information into the study of quantum cryptography like intutive idea and notations. We also learn about the first quantum cryptographic scheme called o ne time pad which allows the perfectly secure encryption of quantum states using classical key, it is anologouse to the classical one time pad cryptographic protocol.

What is the Quantum Cryptography ?

> The goal of quantum cryptography is how can we perform quantum communication to achieve information security.

Quantum Key Distribution(QKD) :

- Entities : Alice and Bob
- Task : Communication of massages like Alice want to send some massage or pictures or even files to the Bob.
- Easedroper(Adversory) : Ajeet try to listen Alice and Bob communication
- Communication Channels : Air, Wire etc can be intercepted by Easedroper
- How can Alice and Bob privent Ajeet from listening their massages. How Alice and Bob should communicate. Why we needed to protect our information.
- Cryptography provides a shafe box called encryption which can encrypt massages inside the box and lock the box with certain key. Then Alice send encrypted messege box to Bob and Bob has a copy of the same key to open that box to get the secret massege. Our box will be safe until easedroper don't have the box key. So, Our information is secure now, but How much key we needed to protect our messages
- Shannon has proved that in order to achieve absolute security we needed a key space as long as our massages which is a huge amount of key itself. it is practically not possible for long massages.
- We needed shorter key space for our long messages. But there is a problem, in order to guarantee information security, we needed to put our adversery under assumption of computationally bounded.
- Today crypto-systems that we use in practice can be broken easly if someone build a quantum computer with large number of qubits. So, We needed to avoid using the concept of short key. thus we needed to find some ways to produce more and more key as long as go i.e Alice can directly say into Bob's ear. Here the problem is Alice and Bob have exactly same key i.e the copy of Alice's Key send to Bob. An Easedroper can intercept the communication and try to listen it. It is the Symmetry Breaking Problem.
- Quantum Communication allows us to break the symmetry for this a no-cloning theorem exist which states that no qubits can be copied. Which provide security that easedroper can't copy the key and we can design some security protocols that allows Alice and Bob to produce key.
- Quantum Key Distribution(QKD) Protocol : it is secure agaist all power-full eavesdroper (arbitrarly large quantum computer)
- Quantum Cryptography started in 1970's when Stephen Wiesner had idea that quantum effects could be exploited in order to achieve cryptographic tasks.
- First QKD Protocol(BB84) Proposed by Bennett and Brassard in 1984.
- E91 Scheme which is based on the quantum entanglement by Arture Ekert. Thus the Quantum Entanglemet proved helpfull in order to understand QKD.
