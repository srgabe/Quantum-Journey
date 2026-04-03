# ⚛️ Quantum Journey: De Moléculas a Materiais Correlacionados

Aprendizado Prático em Computação Quântica com Qiskit: Este repositório documenta minha trajetória de aprendizado em Quantum Computing, aplicando conceitos de mecânica quântica em simulações computacionais de alta complexidade. O projeto evolui de fundamentos de circuitos até a resolução de hamiltonianos fermiônicos.

### 🚀 Estrutura do Projeto

O projeto está dividido em três marcos fundamentais:

1. Fundamentos e Emaranhamento (Estado de Bell): Implementação do circuito básico para gerar o estado de Bell $|$ $\Phi^{+}$ $\rangle$, demonstrando os fenômenos de Superposição e Emaranhamento entre dois qubits. Conceitos: Portas Hadamard (H) e CNOT.

2. Química Quântica: Simulação da Molécula de $H_2$. Utilização do algoritmo VQE (Variational Quantum Eigensolver) para encontrar a energia do estado fundamental da molécula de Hidrogênio em função da distância interatômica. Algoritmo: VQE com Ansatz de Amplitudes Reais. Resultado: Curva de dissociação molecular (Potencial de Morse).

<img width="862" height="556" alt="image" src="https://github.com/user-attachments/assets/15ab6a9c-e2f0-41b3-af32-ec3f235e30db" />


3. Física da Matéria Condensada: Modelo de Hubbard & Grafeno. O ápice do projeto, onde simulei a Transição de Mott em uma rede de dois sítios utilizando o modelo de Fermi-Hubbard. Este modelo é essencial para entender a eletrônica do Grafeno e de materiais com correlações eletrônicas fortes.Técnica: Mapeamento de Jordan-Wigner para transformar operadores fermiônicos (criação/aniquilação) em operadores de spin (qubits).Parâmetros: Hopping ($t = -2.8$ eV) e Interação de Coulomb ($U$ variável).

<img width="870" height="553" alt="image" src="https://github.com/user-attachments/assets/c3a3437e-4452-4849-9a2c-6ece9e73d642" />


### 🛠️ Tecnologias e FrameworksLinguagem: 

Python 3.12

SDK Quântico: Qiskit 1.x (IBM)

Algoritmos: VQE, SLSQP Optimizer.

Simuladores: Qiskit Aer (StatevectorEstimator).

### 🔬 Conclusões de Aprendizado

Este projeto consolidou minha transição da Física Teórica/Experimental (UFU) para a Computação Quântica Aplicada. A principal dificuldade superada foi a adaptação às constantes mudanças nas APIs do Qiskit (versões 0.x para 1.x), o que exigiu uma compreensão profunda da construção manual de tensores fermiônicos e aritmética de operadores de segunda quantização.
