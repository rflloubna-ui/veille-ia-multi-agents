# Learning Log – Projet Veille IA Multi-Agents

## A. Cadrage Cognitif

### 1. Apprentissage exploré

Création d'un système multi-agents avec n8n et Gemini AI pour automatiser la veille technologique.

### 2. Difficulté rencontrée

Erreur de connexion entre les AI Agents et le modèle Gemini.
Problème de configuration API et limitation des requêtes.

---

## B. Problem-Solving

### Décomposition

1. Connexion HTTP Request
2. Création AI Agent
3. Analyse stratégique
4. Génération du rapport final

### Patterns

Le problème ressemblait à une mauvaise orchestration entre plusieurs agents IA.

### Abstraction

Le problème principal venait de la configuration du Chat Model et non du workflow lui-même.

---

## C. Computational Thinking

### 3. Hypothèse

Si tous les agents utilisent le même modèle Gemini correctement configuré, le workflow fonctionnera.

### 4. Stratégie adoptée

- Création d'un credential Gemini valide
- Connexion du Chat Model aux agents
- Test progressif node par node

### 5. Amélioration

Ajout d'un Agent Analyste et d'un Agent Rapporteur pour séparer l'analyse et la génération du rapport.

---

## D. Capitalisation

### 6. Références utilisées

- Documentation n8n
- Google Gemini API
- LangChain Blog
- Cours Agentic AI

### 7. Questions restantes

Comment améliorer la mémoire des agents et automatiser la sauvegarde des résultats dans Google Sheets ?
