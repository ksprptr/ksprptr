```ts
interface Profile {
  name: string;
  username: string;
  roles: readonly string[];
}

export default {
  name: 'Petr Kašpar',
  username: 'ksprptr',
  roles: [
    'Junior Full-Stack Developer',
    'Video Maker',
  ],
} satisfies Profile;
```
