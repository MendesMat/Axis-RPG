# Axis Wiki

---

## 🌍 Locais

### Cidades
```dataview
TABLE resumo AS "Descrição", regiao AS "Região"
FROM "Wiki/Locais/Cidades"
WHERE tipo = "cidade"
SORT file.name ASC
TABLE resumo AS "Descrição", regiao AS "Região"
FROM "Wiki/Locais/Assentamentos"
WHERE tipo = "assentamento"
SORT file.name ASC
