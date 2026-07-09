# Cîrlea Ioan Călin

Automatică & Calculatoare, UTCB (anul II)
cirleajohn@gmail.com · 0787361161
GitHub: github.com/Calin0104 · LinkedIn: linkedin.com/in/călin-ioan-cîrlea

Construiesc aplicații web full-stack. Recent, în echipă: TaskCapture, o aplicație care transformă note libere în task-uri organizate în calendar, live în producție.

## Proiecte

### TaskCapture — app de organizare a task-urilor din text liber &nbsp;&nbsp; [live](https://www.taskcapture.xyz/) · [cod](https://github.com/ed0one/practica_devidevs)

Scrii un gând în română, dezordonat; aplicația separă task-urile, prinde deadline-urile relative („mâine", „până vineri") și le așază în calendar. Proiect de echipă, dezvoltat în practica de vară la DeviDevs.

**Rol: autentificare, protecția rutelor și ecranul de input.**

- Am construit fluxul de autentificare (login/register) cu Supabase Auth, ca fiecare utilizator să-și vadă doar propriile task-uri
- Am scris un middleware Next.js care protejează rutele autentificate și redirecționează spre `/login` utilizatorii nelogați
- Am realizat pagina `/input` (textarea) conectată la endpoint-ul `POST /api/parse-tasks`, care trimite textul liber spre procesare
- Stack: Next.js, TypeScript, Supabase, Vercel. Lucru în echipă cu Git și Jira. Deployed în producție.

## Skills tehnice

```
Limbaje:      C++, Java (solide), JavaScript/TypeScript, Python (baze)
Web:          Next.js, React
Data & infra: Supabase, Vercel, Git
Tooling:      Jira, lucru cu agenți de cod și LLM din terminal
```

## Educație

Universitatea Tehnică de Construcții București — Automatică și Calculatoare, anul II (în curs)
