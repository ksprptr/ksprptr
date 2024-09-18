# Web & App Programmer

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

const ksprptr: CustomProfile = {
  name: 'Petr Kašpar',
  username: 'ksprptr',
  pronouns: 'he/him',
  bio: 'Web & App Programmer',
  knowledge: {
    languages: ['HTML', 'CSS', 'JavaScript', 'TypeScript', 'Java', 'C#'],
    frameworks: ['Next.js', 'React', 'React Native', 'Tailwind CSS', 'ASP.NET'],
    technologies: ['Node.js', 'Prisma'],
  },
  software: {
    ide: ['Visual Studio Code', 'IntelliJ IDEA', 'Rider'],
    devOps: ['Docker', 'Git'],
  },
  contact: [
    { platform: 'email', contact: 'contact@ksprptr.dev' },
    { platform: 'discord', contact: '@ksprptr' },
    { platform: 'instagram', contact: '@ksprptr' },
  ],
};

export default kasparrpetr;
```
