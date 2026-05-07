# AGENTS.md

You are building Personal Life OS.

Read these files before working:
- PRODUCT.md
- TASKS.md
- README.md

Main goal:
Build an MVP web app that turns health, nutrition, and task signals into clear daily execution commands.

Workflow:
1. Pick the first unchecked task in TASKS.md.
2. Implement the smallest working version.
3. Run lint, typecheck, and tests when available.
4. Fix errors.
5. Commit the completed change.
6. Mark the task as done in TASKS.md.
7. Continue to the next unchecked task automatically.

Do not stop after one task.



Rules:
- Mock data before live integrations.
- Keep code simple.
- No overengineering.
- Clean dashboard UI.
- Mobile-friendly layout.
- Health output is coaching, not medical advice.
- Always prefer working MVP over complex architecture.

Tech stack:
- Next.js
- TypeScript
- Tailwind
- Supabase later
- OpenAI API later
- Recharts for charts if needed

Validation:
- Run npm install if needed.
- Run npm run lint if available.
- Run npm run build if available.