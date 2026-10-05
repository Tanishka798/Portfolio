<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

## Portfolio architecture
- Keep the portfolio as a semantic single-page index with anchor navigation; all sections belong to one continuous personal story.
- Store verified project and skill content in a shared browser-safe data module so cards and case studies remain consistent.
- Use CDN asset pointer imports for uploaded portraits and documents to avoid storing binary files in the repository.
- Use an explicit email-draft contact flow without a sending service; never display a successful delivery claim.
- Define all visual styling in the global semantic-token design system and use shared Button and Dialog controls for accessible interactions.
