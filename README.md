# Qiskit starter kit

## Requirements

- python 3.12
- poetry

## How to use

1. サインイン [IBM Quantum](https://quantum.ibm.com/)

2. API Token のコピー

![](./img/ibm-quantum.png)

3. このリポジトリを clone (or [hello_quantum.ipynb](./qiskit_starter_kit/hello_qiskit.ipynb) をご自身の環境で使ってください)

```bash
% git clone git@github.com:wg-quantum/qiskit-starter-kit.git
% cd qiskit-starter-kit
```

4. ターミナルで以下を実行

```bash
% poetry install
% cp .env.example .env
```

5. API Token を `.env` へ記入

6. notebook を実行
