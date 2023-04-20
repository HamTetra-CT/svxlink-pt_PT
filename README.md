# svxlink-pt_PT - Audio & Vozes em Português Portugal para o SVXLink

🎙 Ficheiros de Audio & Vozes em Português Portugal para os repetidores e link que usam SVXLink. Estes ficheiro foram gerados em formato .WAV 16K e estão prontos a serem usados. Obrigado ao colega @CT7ADH pelo trabalho 🫰

---

## ➜ Instruções
### 📣 Para dar voz ao seu repetidor, vamos instalar novos ficheiros de som (formato .WAV 16K) em português.

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

#### 3 - Confirmar que a nova pasta (svxlink-pt_PT-main) foi criada e está bem presente:
```
ls
```

#### 4 - Renomear a recém criada pasta (svxlink-pt_PT-main) para o nome final:
```
sudo mv svxlink-pt_PT-main pt_PT
```

### ✅ Terminado! 
Agora deve passar a linguagem no ficheiro ***"svxlink.conf"*** ou ***"TetraLogic.conf"***  de **us_US** para **pt_PT**.
```
DEFAULT_LANG=pt_PT
```
