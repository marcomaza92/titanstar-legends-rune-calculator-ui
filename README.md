## TitanStar Legends - Rune Mastery Loadout Talent Calculator 9000

### Description

This is a challenge in which I built a calculator to manage and simulate how the talent points are used within runes paths.

The functionality's specifics can be sum up as follows:

- Left click to add points
- Right click to remove points
  - On mobile devices: when you tap on an active rune, it will be deactivated
  - You can try focus / tab-navigate and activate / deactivate by pressing enter on your keyboard
- The user may only use up to 6 points
- Each item only accounts for one point
- Displays current point total
- The user must select the items in order
  - For example: The user may not put a point in the cake without first having put points in the chevrons and the silverware (in that order)

### Tech Stack

- NextJS (App Router)
- pnpm
- TS
- Sass Modules
- Context API
- Vitest
- Stylelint
- Husky

### Setup

#### Install the dependencies

```sh
pnpm install
```

#### Run the development server

```sh
pnpm run dev
```

### Repositories

- [Go to API repository](https://github.com/marcomaza92/titanstar-legends-rune-calculator-api)

### Demo

- [Go to UI MVP](https://titanstar-legends-rune-calculator.vercel.app/)
- [Go to API MVP](https://titanstar-legends-rune-calculator-api.vercel.app/api/paths/)

### Next Steps

- Add Storybook to document components
- Add Atomic Design approach to the components
- Add E2E test with Cypress and Playwright
- Update deployment to AWS
