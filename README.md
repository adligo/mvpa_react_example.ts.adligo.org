# Adligo's Model View Presenter Attendant React Example
### mvpa_react_example.ts.adligo.org

This will be an example of MVP@ using react.

NOTE: The mvpa_react_example2.ts.adligo.org is working better than this project, you will likely want that one.

## Notes

The @ symbol doesn't work in github project names, so it was reverted to the older a in mvp@ vs mvpa.
Next.js uses it's own build system (as of 2026-01-11 moving from Webpack to Turbopack), and isn't compatible with Vite.  


Started one directory above with the existing github project;

```
npx create-next-app@latest mvpa_react_example.ts.adligo.org
# got this error
# Error: Cannot find module '../lightningcss.win32-x64-msvc.node'
# https://github.com/expo/expo/issues/31775
# @ see issues/01_LIGHTNINGCSS.md
# Found this issue post https://github.com/expo/expo/issues/31775
nvm use 20.19.6
nvm use 24.12.0





```