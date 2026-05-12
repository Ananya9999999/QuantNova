---
name: QuantNova Task Template
about: Structured issue template for contributors
title: "[TASK] "
labels: ""
assignees: ""
---

# Task Title

Provide a short and clear title for the task.

---

## Description

Clearly describe:
- What needs to be implemented
- Why this task is important
- Expected behavior/output

Try to explain the task assuming the contributor is new to the project.

---

## Problem Statement

Describe:
- Current limitation/problem
- Why improvement is needed
- User/developer impact

---

## Expected Outcome

Explain what the final implementation should achieve.

**Example:**
- Responsive navbar works on mobile
- Favicon loads correctly
- API endpoint returns valid OHLCV data
- Chart renders without breaking layout

---

## Expected Files to Edit

List files/folders contributors are expected to modify.

**Example:**
```
frontend/src/components/Navbar.tsx
frontend/src/styles/navbar.css
README.md
```

---

## Suggested Tech Stack / Libraries

Mention relevant technologies.

**Example:**
- React
- Vite
- FastAPI
- Tailwind CSS
- TypeScript
- Pandas
- Lightweight Charts

---

## Acceptance Criteria

- [ ] Feature works correctly
- [ ] No console errors or warnings
- [ ] Code follows existing project structure and style
- [ ] Responsive on mobile/tablet (if frontend task)
- [ ] Proper comments/documentation added
- [ ] No breaking changes introduced
- [ ] Tests added (if applicable)

---

## Screenshots / References

(Optional) Add:
- UI references or mockups
- Screenshots of current behavior
- Design inspiration
- Related repositories
- Documentation links

---

## Helpful Resources

Examples:
- [React Documentation](https://react.dev/)
- [Vite Guide](https://vitejs.dev/)
- [FastAPI Docs](https://fastapi.tiangolo.com/)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [QuantNova Frontend Guide](../../docs/FRONTEND.md)
- [QuantNova Setup Guide](../../docs/SETUP.md)

---

## Local Setup Instructions

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

### Backend Setup
```bash
cd backend
python -m venv .venv

# Windows
.\.venv\Scripts\Activate.ps1

# macOS/Linux
source .venv/bin/activate

pip install -e ".[dev]"
uvicorn app.main:app --reload
```

---

## Contribution Guidelines

Before submitting a pull request:
- Pull latest changes from `main` branch
- Keep PR focused on one task
- Avoid unrelated formatting changes
- Test implementation locally before opening PR
- Follow commit message convention (feat:, fix:, docs:, test:, chore:)
- Check [CONTRIBUTING.md](../../CONTRIBUTING.md) for details

---

## Estimated Effort

Choose one:
- 🟢 **Beginner** (~30 mins – 1 hour)
- 🟡 **Intermediate** (~1 – 3 hours)
- 🔴 **Advanced** (3+ hours)

---

## Difficulty Level

- [ ] Beginner
- [ ] Intermediate
- [ ] Advanced

---

## Notes for Contributors

Additional hints for completing this task:
- Avoid modifying unrelated files
- Maintain existing design language and code style
- Ensure compatibility with current architecture
- Ask questions in issue comments if stuck
- Check existing similar implementations for reference
- Reference [CODE_OF_CONDUCT.md](../../CODE_OF_CONDUCT.md) for community guidelines

---

**Questions?** Comment below and maintainers will help! 🚀
