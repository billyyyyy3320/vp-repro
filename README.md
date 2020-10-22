# Repro for vuejs/vuepress#2254

## Increment me: 2

1. Increment the number in the heading below and hit save.
   - If the webpage is automatically refreshed (due to heading change), retry step 1.
   - If the webpage contents is hot-reloaded but no page refresh, continue.
   - If the webpage does not hot-reload at all, go to step 3.
     - In **Browser Console** it should say **[WDS] Errors while compiling. Reload prevented.**
     - Yet in **Terminal** VuePress CLI says “success”.
2. Duplicate a list item at the bottom of the file and hit save.
   - If the webpage contents is hot-reloaded, retry step 2.
   - If the webpage does not hot-reload at all, go to step 3.
     - In **Browser Console** it should say **[WDS] Errors while compiling. Reload prevented.**
     - Yet in **Terminal** VuePress CLI says “success”.
3. Hit the Refresh button to perform a page refresh.
   - Now the webpage should not show up at all, along with error: **Error: ENOENT: no such file or directory, open '/sandbox/node_modules/@vuepress/core/.temp/app-enhancers/global-components-2.js**

Duplicate the below list item:

- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
- Duplicate me
