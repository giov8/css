Aqui está um "cheat sheet" simples e pronto para impressão, contendo exemplos básicos de CSS que podem ser utilizados como apoio na criação do site pessoal:

---

## **CSS Cheat Sheet para Criação de um Site Pessoal**

### **1. Reset Básico de CSS**
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

### **2. Conectando o CSS ao HTML**
```html
<link rel="stylesheet" href="styles.css">
```

### **3. Tipografia Básica**
```css
body {
  font-family: 'Roboto', sans-serif;
  font-size: 16px;
  line-height: 1.6;
  color: #333;
}
h1 {
  font-size: 2.5rem;
  font-weight: bold;
}
p {
  font-size: 1rem;
  margin-bottom: 10px;
}
```

### **4. Definindo Cores**
```css
body {
  background-color: #f9f9f9;
  color: #333;
}
a {
  color: #007BFF;
  text-decoration: none;
}
a:hover {
  color: #0056b3;
}
```

### **5. Layout com Flexbox**
```css
.navbar {
  display: flex;
  justify-content: space-between;
  background-color: #333;
  padding: 10px;
}
.navbar a {
  color: white;
  text-decoration: none;
}
```

### **6. Imagens Responsivas**
```css
img {
  max-width: 100%;
  height: auto;
}
```

### **7. Botões Estilizados**
```css
button {
  background-color: #007BFF;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}
button:hover {
  background-color: #0056b3;
}
```

### **8. Bordas Arredondadas (border-radius)**
```css
.box {
  background-color: #f1f1f1;
  padding: 20px;
  border-radius: 10px; /* Bordas arredondadas */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
```

### **9. Espaçamento com Padding e Margin**
```css
.container {
  padding: 20px;
  margin: 20px 0;
}
```

### **10. Layout com CSS Grid**
```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
.grid-item {
  background-color: #ddd;
  padding: 20px;
  text-align: center;
}
```

### **11. Media Queries para Responsividade**
```css
@media (max-width: 768px) {
  body {
    font-size: 14px;
  }
  .navbar {
    flex-direction: column;
  }
  .grid-container {
    grid-template-columns: 1fr;
  }
}
```
