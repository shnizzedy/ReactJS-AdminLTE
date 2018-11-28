# shnizzedy/ReactJS-AdminLTE

[https://github.com/booleanhunter/ReactJS-AdminLTE](https://github.com/booleanhunter/ReactJS-AdminLTE) version of [the original AdminLTE dashboard](https://github.com/almasaeed2010/AdminLTE) with [lodash@4.17.5](https://www.npmjs.com/package/lodash/v/4.17.5) and [minimatch@3.0.4](https://www.npmjs.com/package/minimatch/v/3.0.4). This fork exists solely to resolve conflicts with those two packages in [Mindlogger](https://github.com/ChildMindInstitute/mindlogger-app-admin-panel), and those two package versions and this README are the only differences from the upstream master.

### Prerequisites:
- [git](https://git-scm.com/)
- [Node & npm](https://www.npmjs.com/get-npm)
- [react](https://www.npmjs.com/package/react)

### Instructions of Usage :
- Run `npm install https://github.com/shnizzedy/ReactJS-AdminLTE`
- Include the stylesheets for the components, similar to the [widgets page](https://github.com/booleanhunter/ReactJS-AdminLTE/blob/master/views/widgets.html)
- Include the library `var reactjsAdminlte = require('adminlte-reactjs')`. You may prefer the AMD style or the import statement.
- You can now begin using the components like this `var ProfileCard = reactjsAdminlte.ProfileCard`.
- If you don't need all the components, then you can choose to include only specific ones rather than the entire library. This can reduce your JS bundle size significantly `var StatTile = require('adminlte-reactjs/src/components/stat-tile')`
