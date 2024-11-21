```typescript
import type { Myself } from '@/types.ts'

(): Myself => ({
  greeting: '👋 Welcome to my profile.',

  personal: {
    name: '🧑‍💻 Alex Svorada',
    title: '⚡ Fullstack Developer',
    location: '🌍 Prague, CZ'
  },

  stack: {
    frameworks: ['💚 Nuxt.js/Vue.js', '🚀 Laravel'],
    languages: ['💙 TypeScript', '🐘 PHP'],
  },

  contact: {
    email: '📨 alex@svorada.eu',
    linkedin: '💼 linkedin.com/in/alexsvorada'
  }
})
```
