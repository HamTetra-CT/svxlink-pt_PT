# svxlink-pt_PT - Audio & Vozes em Português Portugal para o SVXLink
Para dar voz ao seu repetidor, vamos instalar novos ficheiros de som (formato .WAV 16K) em português. Obrigado @CT7ADH

**Instruções -**

#### 1 - Ir para a pasta de sons do SVXLink:
```
cd
```
```
cd /usr/share/svxlink/sounds/
```

#### 2 - Obter os novos ficheiros audio (.ZIP), descompactar e limpar:
```
sudo wget https://github.com/HamTetra-CT/svxlink-pt_PT/archive/master.zip
```
```
sudo unzip master.zip
```
```
sudo rm master.zip
```

#### 3 - Confirmar que a nova pasta (svxlink-pt_PT-master) foi criada e está bem presente:
```
ls
```

#### 4 - Renomear a recém criada pasta (svxlink-pt_PT-master) para o nome final:
```
sudo mv svxlink-pt_PT-master pt_PT
```

### Terminado! Agora deve especificar no ficheiro ***svxlink.conf*** a linguagem para pt_PT.
```
DEFAULT_LANG=pt_PT
```
