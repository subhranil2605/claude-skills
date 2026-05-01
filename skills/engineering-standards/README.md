# 🧠 Engineering Standards Skill

This is a Claude Skill designed to enforce **production-grade software engineering standards**.

---

## 🎯 Purpose

AI-generated code is fast—but often:
- unsafe
- inconsistent
- poorly structured

This skill ensures:
> Every output follows real-world engineering best practices

---

## ⚙️ How It Works

The skill:

1. Loads `SKILL.md` as the base ruleset  
2. Dynamically loads relevant references:
   - security
   - performance
   - code quality
   - reliability
   - devops
   - compliance  
3. Applies rules based on the task  

---

## 🧩 When This Skill Triggers

Use this skill when:

- Writing or reviewing code  
- Designing APIs  
- Handling authentication/security  
- Working with databases  
- Setting up CI/CD  
- Asking:  
  > “Is this the right way to do X?”  

---

## 🛠️ Capabilities

### 🔐 Security
- Auth best practices
- Input validation
- Secret management

### ⚡ Performance
- Query optimization
- Indexing
- Caching strategies

### 🧱 Code Quality
- SOLID principles
- Clean architecture
- Testing standards

### 📊 Reliability
- Logging & monitoring
- SLOs & alerts
- Fault tolerance

### 🚀 DevOps
- CI/CD pipelines
- Docker practices
- Deployment safety

### ⚖️ Compliance
- GDPR / DPDP
- Data classification
- Incident handling

---

## 🧠 Mental Model

Think of this as:

> An AI Tech Lead enforcing standards across your system

---

## 🧪 Example Usage

### Input:
```

Should I store JWT in localStorage?

```

### Output:
- Security risks explained
- Correct approach suggested (HttpOnly cookies)

---

### Input:
```

Review this API

```

### Output:
- Design issues
- Performance problems
- Security gaps

---

## ⚠️ Important Notes

- This does NOT replace engineering knowledge  
- It enforces consistency and best practices  
- Quality depends on correct usage context  

---

## 📁 File Structure

```

SKILL.md              → Core rules
references/
├── security.md
├── performance.md
├── code-quality.md
├── reliability.md
├── devops.md
└── compliance.md

```

---

## 🚀 Goal

> Make good engineering the default, not an afterthought
