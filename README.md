````markdown
# 🌡️ Redes Neurais e Deep Learning: Conversão de Temperaturas

## 🧠 Por que esse exemplo é interessante?

Esse exemplo é perfeito para quem está começando com redes neurais e Deep Learning.  
Aqui, você vê que até mesmo uma tarefa simples, como converter Celsius em Fahrenheit, pode ser aprendida por um modelo de rede neural.

> **A ideia é ver, na prática, como o modelo “descobre” a regra de conversão apenas analisando alguns exemplos!**

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


