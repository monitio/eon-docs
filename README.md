If you see this, please do not use this. It is not done and the Eon repo is still private but Mintlify won't work with private repos for some reason. Please just don't use this as a reference guide or to steal the language I am making. Thank you.

---

# Mintlify - Eon Docs
The docs for [Eon](https://github.com/monitio/eon).

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation changes locally. To install, use the following command

```
npm i -g mint
```

Run the following command at the root of your documentation (where docs.json is)

```
mint dev
```

#### Troubleshooting

- Mintlify dev isn't running - Run `mint install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `docs.json`
