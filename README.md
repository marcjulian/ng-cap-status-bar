# ng-cap-status-bar

Status and Navigation bar styles on Capacitor Android v4 App are overridden from `@capacitor/splash-screen`.

Capacitor Plugins effected:

- @capacitor/status-bar
- [@hugotomazi/capacitor-navigation-bar](https://github.com/hugotomazi/navigation-bar)

Run the capacitor app on an Android device:

```bash
npm i

npm run build

npx cap run android
```

Repeat this when you change the branch between main and splash-screen-plugin.

## Behavior

Behavior on the **main** branch:

Status and Navigation bar color are **red** (`ef4444`).

![Status and Navigation bar color](main.png)

Behavior on the **[splash-screen-plugin](https://github.com/marcjulian/ng-cap-status-bar/tree/splash-screen-plugin)** branch:

Status and Navigation bar color are black. Styles from Status and Navigation bar are not applied.

![Status and Navigation bar color w/ Splash Screen plugin](splash-screen-plugin.png)