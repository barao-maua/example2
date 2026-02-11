# Alternativa: URLs diretas para imagens gratuitas

Se você não conseguir executar o script de download, use estas imagens diretamente nas páginas HTML:

## 🎮 Minecraft (aluno1.html)
```html
<img src="https://images.unsplash.com/photo-1538481199705-c710c4e965fc?w=800&q=80" alt="Construção no Minecraft">
```

## 🍫 Brigadeiro (aluno2.html)
```html
<img src="https://images.unsplash.com/photo-1587314168485-3236d6710814?w=800&q=80" alt="Brigadeiros gourmet">
```

## 🎬 Anime/Série (aluno3.html)
```html
<img src="https://images.unsplash.com/photo-1578632767115-351597cf2477?w=800&q=80" alt="Anime artwork">
```

---

## 📥 Como baixar manualmente

### Opção 1: Usando wget
```bash
cd /home/newton/dev/barao/exemplos/img

wget "https://images.unsplash.com/photo-1538481199705-c710c4e965fc?w=800&q=80" -O minecraft.jpg

wget "https://images.unsplash.com/photo-1587314168485-3236d6710814?w=800&q=80" -O brigadeiro.jpg

wget "https://images.unsplash.com/photo-1578632767115-351597cf2477?w=800&q=80" -O attack-on-titan.jpg
```

### Opção 2: Usando curl
```bash
cd /home/newton/dev/barao/exemplos/img

curl -L "https://images.unsplash.com/photo-1538481199705-c710c4e965fc?w=800&q=80" -o minecraft.jpg

curl -L "https://images.unsplash.com/photo-1587314168485-3236d6710814?w=800&q=80" -o brigadeiro.jpg

curl -L "https://images.unsplash.com/photo-1578632767115-351597cf2477?w=800&q=80" -o attack-on-titan.jpg
```

### Opção 3: Baixar do navegador
1. Acesse os links acima no navegador
2. Clique com botão direito → "Salvar imagem como..."
3. Salve na pasta `img/` com o nome correto

---

## 🌐 Sites recomendados para mais imagens

- **Unsplash**: https://unsplash.com (fotos de alta qualidade, uso livre)
- **Pexels**: https://pexels.com (milhões de fotos e vídeos gratuitos)
- **Pixabay**: https://pixabay.com (mais de 2 milhões de imagens livres)
- **Freepik**: https://freepik.com (ilustrações e vetores gratuitos)

## 🔍 Termos de busca úteis

Para cada tema:
- **Jogos**: "minecraft gameplay", "video games", "gaming setup"
- **Receitas**: "chocolate truffles", "brazilian sweets", "brigadeiro"
- **Animes/Séries**: "anime art", "manga", "japanese animation"
