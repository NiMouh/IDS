# Projeto de Aprendizagem Aplicada a Segurança - Intrusion Detection System

## Autores

- Ana Raquel Neves Vidal (118408)
- Simão Augusto Ferreira Andrade (118345)

## Descrição

Este projeto consiste na implementação de um sistema de deteção de intrusões (‘IDS’) usando machine learning. O sistema é
composto por um modelo de machine learning treinado com um conjunto de dados de tráfego de rede que consegue
classificar o tráfego de rede como normal ou anómalo (binário) e também classificar qual o tipo de ataque (multiclasse).
O modelo é treinado e avaliado com o conjunto de
dados [IoT dataset for Intrusion Detection Systems (‘IDS’) from kaggle](https://www.kaggle.com/datasets/azalhowaide/iot-dataset-for-intrusion-detection-systems-ids).

## Dataset

Este dataset contém dados de tráfego de nove dispositivos IoT diferentes numa janela de intervalo de 10 segundos. Contém
27 atributos. Os atributos são os seguintes:

- MI_dir_L0.1_weight : Mutual Information for a direct connection with a lag of 0.1 (weight)
- MI_dir_L0.1_mean : Mutual Information for a direct connection with a lag of 0.1 (mean)
- MI_dir_L0.1_variance : Mutual Information for a direct connection with a lag of 0.1 (variance)
- H_L0.1_weight : Entropy for a direct connection with a lag of 0.1 (weight)
- H_L0.1_mean : Entropy for a direct connection with a lag of 0.1 (mean)
- H_L0.1_variance : Entropy for a direct connection with a lag of 0.1 (variance)
- HH_L0.1_weight : Joint Entropy for a direct connection with a lag of 0.1 (weight)
- HH_L0.1_mean : Joint Entropy for a direct connection with a lag of 0.1 (mean)
- HH_L0.1_std : Joint Entropy for a direct connection with a lag of 0.1 (std)
- HH_L0.1_magnitude : Joint Entropy for a direct connection with a lag of 0.1 (magnitude)
- HH_L0.1_radius : Joint Entropy for a direct connection with a lag of 0.1 (radius)
- HH_L0.1_covariance : Joint Entropy for a direct connection with a lag of 0.1 (covariance)
- HH_L0.1_pcc : Joint Entropy for a direct connection with a lag of 0.1 (pcc)
- HH_jit_L0.1_weight : Joint Entropy for a direct connection with a lag of 0.1 (weight)
- HH_jit_L0.1_mean : Joint Entropy for a direct connection with a lag of 0.1 (mean)
- HH_jit_L0.1_variance : Joint Entropy for a direct connection with a lag of 0.1 (variance)
- HpHp_L0.1_weight : Conditional Entropy for a direct connection with a lag of 0.1 (weight)
- HpHp_L0.1_mean : Conditional Entropy for a direct connection with a lag of 0.1 (mean)
- HpHp_L0.1_std : Conditional Entropy for a direct connection with a lag of 0.1 (std)
- HpHp_L0.1_magnitude : Conditional Entropy for a direct connection with a lag of 0.1 (magnitude)
- HpHp_L0.1_radius : Conditional Entropy for a direct connection with a lag of 0.1 (radius)
- HpHp_L0.1_covariance : Conditional Entropy for a direct connection with a lag of 0.1 (covariance)
- HpHp_L0.1_pcc : Conditional Entropy for a direct connection with a lag of 0.1 (pcc)
- Device_Name : Device Name
- Attack : Type of attack
- Attack_subType : Subtype of attack
- label : 0 for attacks and 1 for normal samples

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/kJV2ohdI)
