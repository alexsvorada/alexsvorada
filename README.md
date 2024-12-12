```typescript
import type { Myself } from '@/types.ts'
;(): Myself => ({
	greeting: '👋 Welcome to my profile.',

	personal: {
		name: '🧑‍💻 Alex Svorada',
		title: '⚡ Fullstack Developer',
		location: '🌍 Prague, CZ',
	},

	stack: {
		frameworks: ['😻 NestJS', '💚 Nuxt.js/Vue.js'],
		languages: ['💙 TypeScript', '🐘 PHP', '☕ Java'],
		other: ['🎨 TailwindCSS', '🐋 Docker', '🗄️ SQL', '📦 Git'],
	},

	contact: {
		email: '📨 alex@svorada.eu',
		linkedin: '💼 linkedin.com/in/alexsvorada',
	},
})
```
