# Package name

Edit the follwing files:

- [ ] Edit `package.json` 
- [ ] Rename `packages/EDIT_PKG_NAME` folder
- [ ] Edit `packages/EDIT_PKG_NAME/package.json`
- [ ] Check `ci.yml`

Before pushing:

- [ ] Run `pnpm test` to make sure all tests pass.
- [ ] Run `pnpm build` to make sure all packages build.
- [ ] Remove this README.md file
- [ ] Add a README.md file to the package folder
- [ ] Create a symlink by running the following command from the root

```bash
ln -s /packages/EDIT_PKG_NAME/README.md README.md
```

After pushing:

- [ ] Check the CI status on GitHub Actions.
- [ ] Check `.changeset/config.json`  and edit `access` to `public`.

> **Note**: If you think you are missing something, search for `EDIT` in the repo.
