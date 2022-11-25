# Checklist to create a package

Before pushing:

- [ ] Edit `package.json`.
- [ ] Rename `packages/EDIT_PKG_NAME` folder.
- [ ] Edit `packages/EDIT_PKG_NAME/package.json`
- [ ] Check `ci.yml`.
- [ ] Run `pnpm test` to make sure all tests pass.
- [ ] Run `pnpm build` to make sure all packages build.
- [ ] Remove this README.md file.
- [ ] Add a README.md file to the package folder.
- [ ] Create a symlink by running the following command from the root.

```bash
ln -s /packages/EDIT_PKG_NAME/README.md README.md
```

After pushing:

- [ ] Check the CI status on GitHub Actions.
- [ ] Give the changeset bot access to your repo.
- [ ] Add your `NPM_TOKEN` to secrets

When you are ready to publish

- [ ] Check `.changeset/config.json`  and edit `access` to `public`.
- [ ] Add a changeset by running `pnpm changeset` to do your first bump.

> **Note**: If you think you are missing something, search for `EDIT` in the repo.
