# Single Page Menu

"Single Page" means no tabs, no carousel, etc

## Usage

Takes a prop of sections, with the following shape:

```ts
interface MenuItem {
  name: string;
  description: string;
  price: string;
}

interface MenuSection {
  title: string;
  items: MenuItem[];
}

interface Props {
  sections: MenuSection[];
}
```
