# Fullstack web developer

```ts
import { Profile } from 'github';

interface CustomProfile extends Profile {
  knowledge: {
    languages: string[];
    libraries: string[];
    frameworks: string[];
    technologies: string[];
  };
  software: {
    ide: string[];
    devOps: string[];
    tools: string[];
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
  bio: 'Fullstack web developer specializing in fast and modern web applications with Next.js and backend services powered by NestJS.',
  knowledge: {
    languages: ['HTML', 'CSS', 'JavaScript', 'TypeScript', 'Java', 'C#'],
    libraries: ['React'],
    frameworks: ['Next.js', 'NestJS', 'TailwindCSS', 'React Native', 'Expo', 'ASP.NET'],
    technologies: ['Node.js', 'Prisma ORM'],
  },
  software: {
    ide: ['Visual Studio Code', 'DataGrip', 'Rider', 'WebStorm', 'IntelliJ IDEA'],
    devOps: ['Docker', 'Git'],
    tools: ['Insomnia', 'dbdiagram.io'],
  },
  contact: [
    { platform: 'email', contact: 'contact@ksprptr.dev' },
    { platform: 'discord', contact: '@ksprptr' },
    { platform: 'linkedin', contact: '@ksprptr' },
  ],
};

export default ksprptr;
```
