# Edu Hub persona and experience matrix

A static, interactive 4 × 4 matrix covering Business, Analyst, System / Developer and External Partner experiences at 5, 7, 9 and 11 stars. Select a card to reveal its user story, success criteria and user burden. Select it again to return.

## Files

- `public/index.html`: the complete standalone prototype, including its styling and interaction code.
- `vercel.json`: static deployment settings.

No dependencies, build step, backend, API keys or environment variables are required. The content is illustrative product documentation, not a working data-platform integration.

## Deploy with GitHub and Vercel

1. Commit these files to your GitHub repository, preserving the directory structure.
2. In Vercel, choose Add New → Project and import that repository. If necessary, grant the Vercel GitHub integration access to this repository.
3. Select the Other framework preset and the repository root as Root Directory. Use an empty Build Command and `public` as Output Directory. The configuration file already records those settings.
4. Deploy. Open the production URL and verify that the cards flip.
5. Use the stable production project URL in Confluence. Ensure your intended readers can access the deployment under the chosen Vercel protection settings.

Future pushes to the configured production branch trigger production deployments. Other branches normally create preview deployments. Keep the source repository's visibility separate from the website's visitor-access settings.

## Content maintenance

The interactive matrix is embedded in the standalone HTML document. Change the source through the original authoring workflow or carefully update the embedded fragment, then publish the changed HTML through GitHub. This export is standalone and does not require the Codex app to view it.
