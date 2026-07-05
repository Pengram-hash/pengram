# Pengram site

Static website for `pengram.app`, ready for GitHub Pages.

## Legal information

The legal pages are filled with the information from the Kbis issued on
2026-07-01:

- SIREN: `106 852 981`;
- SIRET: `106 852 981 00013`;
- RCS: `106 852 981 R.C.S. Paris`;
- registered office: `16 rue Tiquetonne, 75002 Paris, France`;

If the site is not hosted on GitHub Pages, update the hosting section in
`mentions-legales.html` and `confidentialite.html`.

## GitHub Pages

1. Create a public GitHub repository.
2. Push these files to the `main` branch.
3. In the repository, open `Settings` -> `Pages`.
4. Select `Deploy from a branch`, branch `main`, folder `/root`.
5. Set the custom domain to `pengram.app`.
6. In Infomaniak DNS, point `pengram.app` to GitHub Pages:

```text
A @ 185.199.108.153
A @ 185.199.109.153
A @ 185.199.110.153
A @ 185.199.111.153
CNAME www <your-github-user>.github.io
```

7. Enable `Enforce HTTPS` in GitHub Pages once it becomes available.
