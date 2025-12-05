# Настройка Voicemeeter Banana + Virtual Audio Cable

## 1. Установка необходимых компонентов

1. Скачайте и установите **[Voicemeeter Banana](https://vb-audio.com/Voicemeeter/banana.htm)**.
2. Скачайте и установите **виртуальный кабель – [VB-CABLE](https://vb-audio.com/Cable/index.htm)**.
	1. Распакуйте архив в отдельную папку  
	![_resource/Pasted image 20251205104339.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/fa1050fddb17e14c6b384624989f5eda692a54cd/_resource/Pasted%20image%2020251205104339.png)
	![Pasted image 20251205104402.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/fa1050fddb17e14c6b384624989f5eda692a54cd/_resource/Pasted%20image%2020251205104402.png)
	2. Запустите **VBCABLE_Setup_x64.exe**  
	![Pasted image 20251205104508.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/Pasted%20image%2020251205104508.png)
	3. Нажмите **Install Driver**.
	4. Дождитесь завершения установки.

3. Перезагрузите ПК.

---

## 2. Настройка Voicemeeter Banana

   4. Откройте **Voicemeeter Banana**.
   5. Интерфейс программы:  
   ![voicemeeterpro_x64_tio5ILRnXq.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/voicemeeterpro_x64_tio5ILRnXq.png)

---

### 2.1. Настройка микрофона

6. Нажмите **“Stereo Input”** → раздел **MME (Multimedia)** → выберите свой микрофон  
   (в примере: **Microphone (USB Audio CODEC)**).  
   ![explorer_Ts67eTmLTG.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/explorer_Ts67eTmLTG.png)

7. Активируйте **A3**  
   ![_resource/Pasted image 20251205105714.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/Pasted%20image%2020251205105714.png)
   

   Это нужно, чтобы направлять звук микрофона в виртуальный кабель.

---

### 2.2. Настройка устройства вывода (наушники/колонки)

8. В правом верхнем углу найдите секцию **HARDWARE OUT** (A1, A2, A3).  
   Нажмите **A1** → раздел **MME (Multimedia)** → выберите свои наушники/колонки  
   (пример: **Динамики (USB Audio CODEC)**).  
   ![explorer_MJ5Jwbwo0M.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/explorer_MJ5Jwbwo0M.png)

9. Нажмите **A3** и выберите **CABLE Output (VB-Audio Virtual Cable)**.  
   ![Pasted image 20251205105931.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/Pasted%20image%2020251205105931.png)

---

## 3. Настройка системных устройств Windows

10. Откройте настройки звука:  
    ПКМ по иконке громкости → **Открыть микшер громкости**.  
    ![JunlYIPPqT.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/JunlYIPPqT.png)

11. Установите устройство вывода (наушники/колонки) по умолчанию:  
    **Voicemeeter Input (VB-Audio Voicemeeter VAIO)**  
    **НЕ путать с “Voicemeeter VAIO3 Input”!**  
    ![ApplicationFrameHost_VFA9NUhUlP.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/ApplicationFrameHost_VFA9NUhUlP.png)

12. Установите устройство ввода (микрофон) по умолчанию:  
    **CABLE Output (VB-Audio Virtual Cable)**  
    ![Pasted image 20251205105217.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/Pasted%20image%2020251205105217.png)

---

## 4. Разделение звука браузера в отдельный канал

13. Чтобы браузер выводился в отдельный канал, выберите у него устройство вывода:  
    **Voicemeeter AUX Input (VB-Audio Virtual Cable)**  
    ![Pasted image 20251205110619.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/Pasted%20image%2020251205110619.png)

14. Теперь звук браузера можно направить в микрофон (виртуальный кабель).  
    Для этого нажмите **A3** в секции **VIRTUAL INPUTS** → **Voicemeeter AUX** → **A3**  
    ![Pasted image 20251205110939.png](https://github.com/Oreshec/-Voicemeeter-Banana-Virtual-Audio-Cable/blob/4d911500fd8afa59d582fae9cfd954311c3a8b56/_resource/Pasted%20image%2020251205110939.png)
