# Photos Directory

Place your photos here so they are bundled with the website:
- `photo1.jpg` (or `.png`, `.jpeg`, `.webp`)
- `photo2.jpg`
- `photo3.jpg`

Then match the filenames in `src/config.ts` under `memories`:
```ts
memories: [
  { caption: 'One of my favourite moments', note: '...', image: '/photos/photo1.jpg' },
  { caption: 'Your smile, my favourite view', note: '...', image: '/photos/photo2.jpg' },
  { caption: 'Our little world, miles apart', note: '...', image: '/photos/photo3.jpg' },
]
```
Any photo placed here will automatically show up when anyone opens the website!
