# 🌡️ Redes Neurais e Deep Learning: Conversão de Temperaturas

````markdown
## 🧠 Esse exemplo é interessante se você está começando com redes neurais e Deep Learning, pode ser difícil entender como um modelo realmente aprende.  
Este projeto mostra que até mesmo uma tarefa simples, como converter Celsius em Fahrenheit, pode ser resolvida por uma rede neural — algo que normalmente resolveríamos com uma fórmula matemática.

> A ideia é ver, de forma prática, como o modelo “descobre” a regra de conversão apenas analisando alguns exemplos!

---

## ⚡ Exemplo Simples

Você pode testar a predição de um valor rapidamente assim:

```python
celsius_input = 37.0
predicted_fahrenheit = model.predict([celsius_input])
print(f"{celsius_input}°C = {predicted_fahrenheit[0][0]:.2f}°F")
````

Saída esperada:

```
37.0°C = 98.60°F
```


