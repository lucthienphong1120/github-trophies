# Quick Start

This "hacked" version of `Github Profile Trophy` (ryo-ma) allows you to show all secret trophies.

In this file, some modifications and improvements are added!

About usage, you can check [How to use](/USAGE.md).

## Self Deploy

You'll have to deploy yourself, for [Vercel](/VercelDeployGuide.md)) or [local](/LocalDeployGuide.md)

If you want to configure which trophies you automatically get, configure these booleans in [src/card.ts](/src/trophy.ts#L13)

```ts
let wantAllSuperRank = true;
let wantMultipleLang = true;
let wantLongTimeAccount = true;
let wantAncientAccount = false;
let wantNewAccount = false;
let wantMultipleOrganizations = true;
```

If you choose to use my deployment, it would be really appreciated if you gave me a star 🙃.
