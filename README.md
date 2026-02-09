/** @type {import('next').NextConfig} */
const nextConfig = {
  reactStrictMode: true,
  swcMinify: true,
}

module.exports = nextConfig{
  "buildCommand": "next build",
  "framework": "nextjs",
  "nodeVersion": "18.x"
}export default function Home() {
  return (
    <div style={{ padding: '40px', textAlign: 'center' }}>
      <h1>Welcome to Shimul Hossain's Portfolio</h1>
      <p>Your deployment is now working!</p>
      <nav style={{ marginTop: '20px' }}>
        <a href="/about" style={{ marginRight: '20px' }}>About</a>
        <a href="/projects">Projects</a>
      </nav>
    </div>
  )
}export default function About() {
  return (
    <div style={{ padding: '40px' }}>
      <h1>About Me</h1>
      <p>This is the about page.</p>
      <a href="/">← Back to Home</a>
    </div>
  )
}export default function Projects() {
  return (
    <div style={{ padding: '40px' }}>
      <h1>My Projects</h1>
      <p>This is the projects page.</p>
      <a href="/">← Back to Home</a>
    </div>
  )
}{
  "name": "shimulhossain",
  "version": "1.0.0",
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "^14.0.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  }
}{
  "name": "shimulhossain",
  "version": "1.0.0",
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "^14.0.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  }
}
