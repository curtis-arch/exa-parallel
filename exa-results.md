## 📄 Result 1

### **Title:** Documentation - TypeScript 5.9

  * **Rank:** 1
  * **URL:** `https://www.typescriptlang.org/docs/handbook/release-notes/typescript-5-9.html`
  * **Published Date:** 2025-08-25T00:00:00.000Z
  * **Author:** (N/A)
  * **Score:** 0.5455842614173889
  * **Content:** Was this page helpful?

\# TypeScript 5.9

## Minimal and Updated `tsc --init`

For a while, the TypeScript compiler has supported an `--init` flag that can create a `tsconfig.json` within the current directory.
In the last few years, running `tsc --init` created a very “full” `tsconfig.json`, filled with commented-out settings and their descriptions.
We designed this with the intent of making options discoverable and easy to toggle.

However, given external feedback (and our own experience), we found it’s common to immediately delete most of the contents of these new `tsconfig.json` files.
When users want to discover new options, we find they rely on auto-complete from their editor, or navigate to [the tsconfig reference on our website](https://www.typescriptlang.org/tsconfig/) (which the generated `tsconfig.json` links to\!).
What each setting does is also documented on that same page, and can be seen via editor hovers/tooltips/quick info.
While surfacing some commented-out settings mi

-----

## 📄 Result 2

### **Title:** Announcing TypeScript 5.9 - TypeScript

  * **Rank:** 2
  * **URL:** `https://devblogs.microsoft.com/typescript/announcing-typescript-5-9/`
  * **Published Date:** 2025-08-01T00:00:00.000Z
  * **Author:** Daniel Rosenwasser
  * **Score:** 0.5097581148147583
  * **Content:** [Skip to main content](https://www.google.com/search?q=javascript:void\(0\))

[Daniel Rosenwasser](https://devblogs.microsoft.com/typescript/author/danielrosenwasser)

Principal Product Manager

Today we are excited to announce the release of TypeScript 5.9\!

If you’re not familiar with TypeScript, it’s a language that builds on JavaScript by adding syntax for types.
With types, TypeScript makes it possible to check your code to avoid bugs ahead of time.
The TypeScript type-checker does all this, and is also the foundation of great tooling in your editor and elsewhere, making coding even easier.
If you’ve written JavaScript in editors like Visual Studio and VS Code, TypeScript even powers features you might already be using like completions, go-to-definition, and more.
You can [learn more about TypeScript at our website](https://typescriptlang.org/).

But if you’re already familiar, you can start using TypeScript 5.9 today\!

```
npm install -D typescript

```

Let’s take a look at what’s new in TypeScript 5.9\!

  - [Mini

-----

## 📄 Result 3

### **Title:** Announcing TypeScript 5.9 Beta - TypeScript

  * **Rank:** 3
  * **URL:** `https://devblogs.microsoft.com/typescript/announcing-typescript-5-9-beta/`
  * **Published Date:** 2025-07-08T00:00:00.000Z
  * **Author:** Daniel Rosenwasser
  * **Score:** 0.517676591873169
  * **Content:** [Skip to main content](https://www.google.com/search?q=javascript:void\(0\))

[Daniel Rosenwasser](https://devblogs.microsoft.com/typescript/author/danielrosenwasser)

Principal Product Manager

Today we are excited to announce the availability of TypeScript 5.9 Beta.

To get started using the beta, you can get it through npm with the following command:

```
npm install -D typescript@beta

```

Let’s take a look at what’s new in TypeScript 5.9\!

  - [Minimal and Updated `tsc --init`](https://www.google.com/search?q=%5Bhttps://devblogs.microsoft.com/typescript/announcing-typescript-5-9-beta/%23minimal-and-updated-tsc---init%5D\(https://devblogs.microsoft.com/typescript/announcing-typescript-5-9-beta/%23minimal-and-updated-tsc---init\))
  - [Support for `import defer`](https://www.google.com/search?q=%5Bhttps://devblogs.microsoft.com/typescript/announcing-typescript-5-9-beta/%23support-for-import-defer%5D\(https://devblogs.microsoft.com/typescript/announcing-typescript-5-9-beta/%23support-for-import-defer\))
  - [Support for `--module node20`](https://www.google.com/search?q=%5Bhttps://devblogs.microsoft.com/typescript/announcing-typescript-5-9-beta/%23support-for---module-node20%5D\(https://devblogs.microsoft.com/typescript/announcing-typescript-5-9-beta/%23support-for---module-node20\))
  - [Summary Descriptions in DOM APIs](https://devblogs.microsoft.com/typescript/announcing-typescript-5-9-beta/#summary-descriptions-in-dom-apis)
  - [Expandable Hovers (Previe

-----

## 📄 Result 4

### **Title:** Announcing TypeScript 5.9 RC - TypeScript

  * **Rank:** 4
  * **URL:** `https://devblogs.microsoft.com/typescript/announcing-typescript-5-9-rc/`
  * **Published Date:** 2025-07-25T16:53:10.000Z
  * **Author:** Daniel Rosenwasser
  * **Score:** 0.49825572967529297
  * **Content:** We use optional cookies to improve your experience on our websites, such as through social media connections, and to display personalized advertising based on your online activity. If you reject optional cookies, only cookies necessary to provide you the services will be used. You may change your selection by clicking “Manage Cookies” at the bottom of the page. [Privacy Statement](https://go.microsoft.com/fwlink/?LinkId=521839) [Third-Party Cookies](https://aka.ms/3rdpartycookies)

AcceptRejectManage cookies

[Skip to main content](https://www.google.com/search?q=javascript:void\(0\))

[Daniel Rosenwasser](https://devblogs.microsoft.com/typescript/author/danielrosenwasser)

Principal Product Manager

Today we are excited to announce the Release Candidate (RC) of TypeScript 5.9\!

To get started using the Release Candidate, you can get it through npm with the following command:

Copy

```
npm install -D typescript@rc

```

Let’s take a look at what’s new in TypeScript 5.9\!

  - [Minimal and Updated `tsc --init`](https://de

-----

## 📄 Result 5

### **Title:** Announcing TypeScript 5.8 Beta - TypeScript

  * **Rank:** 5
  * **URL:** `https://devblogs.microsoft.com/typescript/announcing-typescript-5-8-beta/`
  * **Published Date:** 2025-01-29T00:00:00.000Z
  * **Author:** Daniel Rosenwasser
  * **Score:** 0.503541886806488
  * **Content:** [Skip to main content](https://www.google.com/search?q=javascript:void\(0\))

[Daniel Rosenwasser](https://devblogs.microsoft.com/typescript/author/danielrosenwasser)

Principal Product Manager

Today we are excited to announce the availability of TypeScript 5.8 Beta.

To get started using the beta, you can get it through npm with the following command:

```
npm install -D typescript@beta

```

Let’s take a look at what’s new in TypeScript 5.8\!

## Checked Returns for Conditional and Indexed Access Types

Consider an API that presents a set of options to a user:

```
/**
 * @param prompt The text to show to a user.
 * @param selectionKind Whether a user can select multiple options, or just a single option.
 * @param items Each of the options presented to the user.
 **/
async function showQuickPick(
 prompt: string,
 selectionKind: SelectionKind,
 items: readonly string[],
): Promise {
 // ...
}

enum SelectionKind {
 Single,
 Multiple,
}

```

The intent with `showQuickPick` is that it shows a UI element that can allow
