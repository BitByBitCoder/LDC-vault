

### What is a System Bus?

A **system bus** is the **main communication pathway** inside a computer that connects the CPU, memory, and input/output devices.
[Address Bus](Address%20Bus.md)
[[Control Bus]]
[Data bus](Data%20bus.md)

 These three are the **main communication buses** inside a computer. Think of them as different “roads” with different jobs.

---

## 🔹 1. Address Bus

![Image|234](https://images.openai.com/static-rsc-4/tmoUWpHCbb-2DJQi9Heer7mY6Tskov2APFQSah7oe-Xh2aBE6kKT0rtMXUTHaxUTg_J-RZR0tToSHh1JQbm27_TXExIF_DzrJGHSGWud-DTsKz9tOTqvBiG8aurrwuyK9waj4v2Ncz6h4HqR0Z0b4RoyaTdQN4vltfYvdA8142d88Pkv5Z15DbgsIIVwPJ2Z?purpose=fullsize)

![Image|227](https://images.openai.com/static-rsc-4/FppqNCKPgjDNjJCOZwIUZ7_RqUoyDhWI-DadzGUVR3EUidSQkYOr9WZiKTcP3DWNx_o0fwhk9GCy8Fqo7Utt1hmcWYGNSrB9Bs0pw6Da_bq0YQnH4wqV2J-yEwv5VHosQjS0ZuPFcCbBZ6rW59rXAXDw83-YebVRUIPFvgE8TbZ4uQJAvVQmnroyzx_LgO3u?purpose=fullsize)

![Image|202](https://images.openai.com/static-rsc-4/CGqYbbM7EFxJ6-yNjfSd_z2rLnRXbMYS7bQhkDvLZud-SL1Ig7eUaAKkJGA1S_pmlw9nM3kTNdL58dGwSpRUEjmuz60swVxy_xNZ4x-TcKIemLoUhwDCuDbsT44-rkoE7wGgo6JbggtnN0IWNQ1sAWCz1gjvUjQMrirmhYeXu1qKgj-3XSaStFn8nD1u4fVz?purpose=fullsize)

![Image|213](https://images.openai.com/static-rsc-4/Ve3Rj2zIUQnDslQpsQFTHmUyXVZgW0c4V-hr1qBt6AD6WXVKtU-5jj3bUkOnpsOoES_Hk4cT05yY1B82BydQn5YErpvwBrZpfu7dj3l25hQjjYfWGaNFUNigdkUbi3nVXo3vcPomNOxoOeo92jsX2EwQ9ZC45pT-P6x_I57vYF44rkFavyRC7OjJHcUxYgVL?purpose=fullsize)

![Image|144](https://images.openai.com/static-rsc-4/BI45i0SLopx1FzI1aQARjgigAx_M8be-wVPLA6Amw6s97-A6pwdo1V4p67jQo4a6Dz69tcZG6QuHPKuhze2hSxOTrt5Vnkd6jb-U6dHwwoc6Rmx4lIoWFYjrv_F3wZiQboyZTj8BnBXb5IgWwLAsbcPlSOFHDkdkID-siKCj10Gwh9XAWGD0A64F0pu9U0Ga?purpose=fullsize)

![Image|158](https://images.openai.com/static-rsc-4/hwK83mS6jj_U9xjSRSQPrJxxtD5jAeGb9YyQe1yV81crwC3fZ_uxP1LHECSiwR7Sjr6eTiL0bdi5uv21TtTyD3vuk-7IXxROZuEiIYOyMIbJl7srQeZ7M72_-6fcxCwU-SYsCksDR34jx1NpCMpfbZmMi-gf-vQ-jN2HDWzQNmPNlqROK6QA2pLpD9MmZ_5s?purpose=fullsize)

**What it does:**  
Carries the **location (address)** of data.

- Direction: **One-way (CPU → Memory/I/O)**
    
- Purpose: Tells _where_ to read/write
    
- Example: “Go to memory location 1000”
    

👉 It does **not carry data**, only the address.

---

## 🔹 2. Data Bus

![Image|164](https://images.openai.com/static-rsc-4/vqpQmlNIuqVXDFOKKnsfxbSRjYcoU7aLYvJyffNyD_eucgF0bcs2GMp8_il7HD33jvfc9lJIybn8_bqWThmwIFN7uwsPvbmQQTgUr7SCk3SSWPH4zocAa0g2dB5bs75nU1R0B_2DwsnneywOE6fIg1Il-OjDzbItxDZJOriyXsH9PFWRp_Ga_meLMA0iuVMt?purpose=fullsize)
![Image|120](https://images.openai.com/static-rsc-4/FppqNCKPgjDNjJCOZwIUZ7_RqUoyDhWI-DadzGUVR3EUidSQkYOr9WZiKTcP3DWNx_o0fwhk9GCy8Fqo7Utt1hmcWYGNSrB9Bs0pw6Da_bq0YQnH4wqV2J-yEwv5VHosQjS0ZuPFcCbBZ6rW59rXAXDw83-YebVRUIPFvgE8TbZ4uQJAvVQmnroyzx_LgO3u?purpose=fullsize)
![Image|89](https://images.openai.com/static-rsc-4/FppqNCKPgjDNjJCOZwIUZ7_RqUoyDhWI-DadzGUVR3EUidSQkYOr9WZiKTcP3DWNx_o0fwhk9GCy8Fqo7Utt1hmcWYGNSrB9Bs0pw6Da_bq0YQnH4wqV2J-yEwv5VHosQjS0ZuPFcCbBZ6rW59rXAXDw83-YebVRUIPFvgE8TbZ4uQJAvVQmnroyzx_LgO3u?purpose=fullsize)

![Image|176](https://images.openai.com/static-rsc-4/cPp0T8aQwkvldQiMjk467nJgjyR26to1zh3HlD1z1go954AFc4_RcnMXz7ac220nZkcA-zEPIcE03Bs3Bgtk9LWS1w92q5dAhKwagdCaaxLN67kc1kR5NQ6lnZUuw2DS1v2nx09A-DGH5pbaQT6EOEIrAOZshmX0kolMXOod9C4z3p3WAzCgOAv_2J173Dsc?purpose=fullsize)

![Image|210](https://images.openai.com/static-rsc-4/Ve3Rj2zIUQnDslQpsQFTHmUyXVZgW0c4V-hr1qBt6AD6WXVKtU-5jj3bUkOnpsOoES_Hk4cT05yY1B82BydQn5YErpvwBrZpfu7dj3l25hQjjYfWGaNFUNigdkUbi3nVXo3vcPomNOxoOeo92jsX2EwQ9ZC45pT-P6x_I57vYF44rkFavyRC7OjJHcUxYgVL?purpose=fullsize)

![Image|237](https://images.openai.com/static-rsc-4/XQuOG9dRPQmYV17Z20YJV2kwsfjQ1MLJDo_Ye8ce9Jb9-pcEj4Tz_N9Ir_WUYKn3WlPGRlZQ2ba-MvWvW1-lX-OzAVEFpjRN5I0HiWMmZpXplGhcVZDl8QPfACYJ33oBM_pKSv63ysN4IhuGEeJDZSsDLNy7aLsYSp9o7dyo16ecFRzvhMJPCBHX4xywd5HR?purpose=fullsize)

**What it does:**  
Carries the **actual data**.

- Direction: **Two-way (CPU ↔ Memory/I/O)**
    
- Purpose: Transfers data back and forth
    
- Example: Sends/receives the value stored at an address
    

👉 This is the **“actual information highway.”**

---

## 🔹 3. Control Bus

![Image](https://images.openai.com/static-rsc-4/FppqNCKPgjDNjJCOZwIUZ7_RqUoyDhWI-DadzGUVR3EUidSQkYOr9WZiKTcP3DWNx_o0fwhk9GCy8Fqo7Utt1hmcWYGNSrB9Bs0pw6Da_bq0YQnH4wqV2J-yEwv5VHosQjS0ZuPFcCbBZ6rW59rXAXDw83-YebVRUIPFvgE8TbZ4uQJAvVQmnroyzx_LgO3u?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Uw_ONiQcqQDrWfKKYJFC11UKXnQOXp81xqV9pYAlm05y-0TMNMN66ys4LYserMWuRpvGc5t3C-b4UYw-t0vX6aVy0Sd5j2tWcnHbv39injlM_TL6TGMJ1fAPHnAmTpn7LWIWXd6A-XHJdBZXnQvRxQsMRFDtSmIp6_ivZEodu7juRFboKLdky6ulvfktxlBE?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/XQuOG9dRPQmYV17Z20YJV2kwsfjQ1MLJDo_Ye8ce9Jb9-pcEj4Tz_N9Ir_WUYKn3WlPGRlZQ2ba-MvWvW1-lX-OzAVEFpjRN5I0HiWMmZpXplGhcVZDl8QPfACYJ33oBM_pKSv63ysN4IhuGEeJDZSsDLNy7aLsYSp9o7dyo16ecFRzvhMJPCBHX4xywd5HR?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/uP6XJ0QyeD2sBE6A_YPS1UujYuYCMpOZ3sRlMyzfAiACP1VhJiHhos01u5V7f9rrd-ZWZNNXBUM_lK0puwiNolSXzdJ2_u4hAGOXCMNnCI0Os-lgQyvsiVs2WC_RU8w-ip_Po2KfAtcSwk2DDrdG3QPO1R4nKdJX0wtYLRr8nxRn0mY80AmsNTCvOrnBqSNy?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/haFycHsSyZydHEPnnPjCA7wLencBNsRMeWzm6fDOibIdsTAPLMI7BmM4ZdGCxALi6tw2evo4IuRZD--ajryTfK9uCbB6OzHFtIR-76G07SSvB-7XeHLbfz278k-jOjncg-6NORK_0sf5GRGJUeSS8EzxtD1q27A9KkHScT8i5q8B_Of_QKWh_R0xtxXxF0Cz?purpose=fullsize)

**What it does:**  
Carries **control signals** to manage operations.

- Direction: **Both ways (mostly CPU ↔ devices)**
    
- Purpose: Tells _what to do_
    
- Examples:
    
    - Read
        
    - Write
        
    - Interrupt
        
    - Reset
        

👉 It’s like the **traffic controller**.

---

## 🔥 Simple analogy (easy to remember)

|Bus|Meaning|
|---|---|
|Address Bus|**Where** to go|
|Data Bus|**What** to carry|
|Control Bus|**How/when** to do it|

---

If you want, I can give you a **real-life example step-by-step (like CPU reading a number from RAM)** — that makes it stick instantly.