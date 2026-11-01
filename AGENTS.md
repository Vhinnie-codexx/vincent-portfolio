# Portfolio development instructions for Codex

This is Vincent Nzubechukwu's existing personal portfolio, originally developed using ChatGPT Work. **Continue this project; do not recreate or redesign it wholesale.**

## Stack and hosting
- React, TypeScript, Vite, Tailwind CSS 4
- Deployment configured for Netlify: `npm run build`, publish `dist/`, Node 22.
- Live URL listed in README: https://vincent-nzubechukwu.netlify.app/

## Rules
1. Preserve current brand, animations, working sections, links, responsive layout, and written content unless specifically requested otherwise.
2. Read existing components and styles before editing. Keep changes focused and reviewable.
3. Do not represent fictional practice work as actual client engagements. Keep project details accurate.
4. Do not add secret tokens or paid services. Do not introduce new dependencies unnecessarily.
5. After a change, run `npm ci` (when dependencies are absent), `npm run lint`, and `npm run build`. Report results accurately.
6. Before deployment, check the responsive experience, keyboard navigation, reduced-motion behavior, console errors, links, and interactions. Where available, use Playwright to automate smoke tests.
7. Deploy via the existing Netlify connection only after the change is reviewed and checks pass; do not silently change domains or hosting.

## Design skill setup (optional, verify sources/permissions)
- Consider Impeccable (https://impeccable.style/) and Taste Skill (https://www.tasteskill.dev/) to review and refine design. Install only the relevant verified skills into this repository's Codex environment, not arbitrary bundles.
- A skills installation in a local Codex environment is separate from editing this repository; verify that skills are actually recognized in Codex.
- Use design skills as review aids, not authority to overwrite the current portfolio appearance.

## Immediate next steps
1. Compare the GitHub main branch with the latest work from ChatGPT Work; transfer any unpublished edits first.
2. Inspect existing layout and confirm visual baseline.
3. Install and confirm suitable Codex design skills in the actual Codex environment.
4. Implement requested changes on a feature branch, validate and preview before merge/deployment.
