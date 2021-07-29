```
# mac_hipotetico
python3 simulador_mac_hipotetico.py -t 1000 -i 0.1 123 1923 15673 1193650000 > ./outputs_dos_experimentos/experimento_5/mac_hipotetico_assimetrico.txt
python3 simulador_mac_hipotetico.py -t 1000 -i 0.1 10000000 10000000 10000000 10000000 > ./outputs_dos_experimentos/experimento_5/mac_hipotetico_simetrico.txt

# csma_nao_persistente
python3 simulador_csma_nao_persitente.py -t 1000 -i 0.1 10000000 10000000 10000000 10000000 > ./outputs_dos_experimentos/experimento_5/csma_nao_persitente_simetrico.txt
python3 simulador_csma_nao_persitente.py -t 1000 -i 0.1 123 1923 15673 1193650000 > ./outputs_dos_experimentos/experimento_5/csma_nao_persitente_assimetrico.txt

# slotted aloha
python3 simulador_aloha_slotted.py -t 1000 -i 0.1 10000000 10000000 10000000 10000000 > ./outputs_dos_experimentos/experimento_5/aloha_slotted_simetrico.txt
python3 simulador_aloha_slotted.py -t 1000 -i 0.1 123 1923 15673 1193650000 > ./outputs_dos_experimentos/experimento_5/aloha_slotted_assimetrico.txt

# pure aloha
python3 simulador_aloha_puro.py -t 1000 -i 0.1 10000000 10000000 10000000 10000000 > ./outputs_dos_experimentos/experimento_5/aloha_puro_simetrico.txt
python3 simulador_aloha_puro.py -t 1000 -i 0.1 123 1923 15673 1193650000 > ./outputs_dos_experimentos/experimento_5/aloha_puro_assimetrico.txt
```