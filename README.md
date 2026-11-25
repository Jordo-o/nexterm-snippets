# Corpobit Snippets for Nexterm

This source contains 772 snippets adapted from [corpobit/nexterm-snippets](https://github.com/corpobit/nexterm-snippets). Snippet names are prefixed with their category. Each file includes the original command, its description, and any placeholders and default values.

## Add to Nexterm

1. In Nexterm, go to **Settings → Sources → Add**.
2. Name the source **Corpobit Snippets** and enter this URL:

   ```text
   https://raw.githubusercontent.com/Jordo-o/nexterm-snippets/main
   ```

3. Save the source, then select **Corpobit Snippets** in the **Snippets** panel.

## Host your own copy

Keep `NTINDEX` and the `snippets/` directory together at the root of a public Git repository or in a directory on an HTTPS server that Nexterm can reach. For a public GitHub repository on the `main` branch, use `https://raw.githubusercontent.com/<owner>/<repository>/main` as the source URL. For an HTTPS server, use the URL of the directory containing `NTINDEX`. To check the URL, open `<source-url>/NTINDEX`.

To publish an extracted copy with Git, create an empty public repository on GitHub. Open a terminal in the extracted directory and replace `OWNER` and `REPOSITORY` with your own values.

```sh
git init -b main
git add .gitattributes LICENSE README.md NTINDEX snippets
git commit -m "Add converted Nexterm snippets"
git remote add origin https://github.com/OWNER/REPOSITORY.git
git push -u origin main
```

## Placeholders

531 snippets contain placeholders such as `{container_name}`. Nexterm can run a snippet as soon as you select it. To supply values, copy the command from the `.snippet` file, replace its placeholders, and run it in the appropriate shell or client. Each template's description lists its placeholders and any default values.

See [LICENSE](LICENSE) for the original license.
