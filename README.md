# storybook-8-typescript-snippets README

Provides basic snippets for Storybook 8 with React and TypeScript.

## Usage

Enter `sb8` in the supported language file and select the snippet.

Supported languages

- typescript
- typescriptreact

## Snippets

### typescript, typescriptreact

```tsx
import type { Meta, StoryObj } from "@storybook/react";
import Component from "./Component";

const meta = {
  component: Component,
} satisfies Meta<typeof Component>;
export default meta;

type Story = StoryObj<typeof meta>;

export const Default = {
  args: {
  },
} satisfies Story;

```
