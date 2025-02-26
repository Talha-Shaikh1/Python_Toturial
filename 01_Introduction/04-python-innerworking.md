## 4. Python Inner Working (Kaise Kaam Karta Hai?)
Jab tum Python ka program likhte ho aur run karte ho, to yeh 4 steps follow hotay hain:

1. **Parsing & Compilation:** Python code ko **Bytecode** me convert karta hai (.pyc file)
2. **PVM Execution:** Python Virtual Machine (PVM) is Bytecode ko execute karta hai
3. **Memory Management:** Python automatic memory allocation karta hai (Garbage Collection)
4. **Interpreted Execution:** Python code ko **directly CPU nahi samajhta**, pehle interpreter aur PVM process kartay hain.

### **Example:**
```python
x = 10
y = 20
print(x + y)
```

### **Kaise Execute Hota Hai?**
1. **Step 1:** Python interpreter is code ko parse karta hai aur syntax check karta hai.
2. **Step 2:** Code ko **bytecode** me convert karta hai.
3. **Step 3:** PVM bytecode execute karta hai.
4. **Step 4:** Output terminal par show hota hai.

Is wajah se Python **cross-platform** hoti hai aur Windows, Mac, Linux sab pe chal sakti hai.