# Zadania - Interactive Math Problem Solver

An interactive step-by-step math problem solver with smooth animations and a clean UI.

## Features

- 5-state cycle for each step: hint → expression → highlight → complete → reset
- Smooth transitions without page jumping
- Completed view showing consolidated solution
- Responsive dark theme design
- KaTeX for beautiful math rendering

## Local Development

```bash
python3 -m http.server 8000
# or
npx http-server
```

Then open http://localhost:8000

## Deployment

This project is designed to be deployed on Vercel. Simply connect this repository to Vercel and it will automatically deploy.