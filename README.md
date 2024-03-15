# Full-Stack Website Developer

```ts
import { Profile } from 'github';

interface CustomProfile extends Profile {
  knowledge: {
    languages: string[];
    frameworks: string[];
    technologies: string[];
  };
  software: {
    ide: string[];
    devOps: string[];
  };
  contact: {
    platform: string;
    contact: string;
  }[];
}

const kasparrpetr: CustomProfile = {
  name: 'Petr Kašpar',
  username: 'kasparrpetr',
  pronouns: 'he/him',
  bio: 'Full-Stack Website Developer.',
  knowledge: {
    languages: ['HTML', 'CSS', 'JavaScript', 'TypeScript', 'Java', 'C#'],
    frameworks: ['Next.js', 'React', 'ASP.NET'],
    technologies: ['TailwindCSS', 'Node.js', 'Prisma'],
  },
  software: {
    ide: ['Visual Studio Code', 'IntelliJ IDEA', 'Rider'],
    devOps: ['Docker'],
  },
  contact: [
    { platform: 'email', contact: 'contact@kasparpetr.com' },
    { platform: 'discord', contact: 'dortwess' },
    { platform: 'instagram', contact: '@kasparrpetr' },
  ],
};

export default kasparrpetr;
```
