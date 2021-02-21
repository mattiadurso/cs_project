# Cybersecutity final project, January 2021
This project implements a two-party secure function evaluation[5] using Yao’s garbled circuit [2] protocol. This project uses a modified version of Ojroques’ garbled-circuit repository[3] in order to compute a secure sum between two parties.
In this project, two parties Alice and Bob compute the sum on their sets without sharing the value of each of their inputs with the opposit party. Alice is the circuit creator (the garbler) while Bob is the circuit evaluator. Alice creates the Yao circuit and sends it to Bob along with her encrypted inputs. Bob then computes the results and sends them back to Alice.
