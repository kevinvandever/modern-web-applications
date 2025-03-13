---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## Building and Deploying Modern Web Applications Using AI
  A Beginner's Guide to bolt.new, StackBlitz, GitHub, and Netlify
drawings:
  persist: false
css: unocss
---

# Building and Deploying Modern Web Applications Using AI

<span class="text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-blue-500">
A Beginner's Guide to bolt.new, StackBlitz, GitHub, and Netlify
</span>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
layout: intro
---

# Kevin Vandever
## <span class="text-blue-400">AI Technology Consultant</span>

- 20+ years leading technical innovation and digital transformation
- Published author and technical mentor
- <span class="text-green-400">Specialist in AI integration and workflow automation</span>
- Expert in bridging technical and business needs

<div class="mt-4">
  <div class="flex flex-col gap-2">
    <div class="flex items-center text-blue-500 hover:text-blue-600 transition-colors duration-200">
      <carbon:logo-linkedin class="inline mr-1"/> https://www.linkedin.com/in/kevinvandever/
    </div>
    <div class="flex items-center text-blue-500 hover:text-blue-600 transition-colors duration-200">
      <carbon:globe class="inline mr-1"/> Website: https://vandevercollective.com
    </div>
  </div>
</div>

---
layout: default
background: 'linear-gradient(to right bottom, #2a1f3d, #2d2047, #302151, #32225b, #342365)'
class: 'text-white'
---

# Workshop Overview

<div class="grid grid-cols-2 gap-8">
<div>

### <span class="text-yellow-300">The Challenge</span>
- <span class="text-blue-300">Complex development cycles</span>
- <span class="text-green-300">Slow traditional methods</span>
- <span class="text-purple-300">Integration challenges</span>
- <span class="text-pink-300">Manual process risks</span>

### <span class="text-yellow-300">The Solution</span>
- <span class="text-blue-300">AI-powered automation</span>
- <span class="text-green-300">Streamlined workflows</span>
- <span class="text-purple-300">Modern version control</span>
- <span class="text-pink-300">Best practices</span>

</div>

<div>

### <span class="text-yellow-300">Key Benefits</span>
- <span class="text-blue-300">Rapid development</span>
- <span class="text-green-300">Error reduction</span>
- <span class="text-purple-300">Better code quality</span>
- <span class="text-pink-300">Faster deployments</span>

### <span class="text-yellow-300">Expected Outcomes</span>
- <span class="text-blue-300">Production-ready apps</span>
- <span class="text-green-300">Automated processes</span>
- <span class="text-purple-300">Enhanced skills</span>
- <span class="text-pink-300">Modern practices</span>

</div>
</div>

---
layout: default
background: 'linear-gradient(to right bottom, #2a1f3d, #2d2047, #302151, #32225b, #342365)'
class: 'text-white'
---

# What We Will Cover

<div class="grid grid-cols-2 gap-8">
<div>

### <span class="text-yellow-300">Project Creation</span>

- <span class="text-blue-300">AI-powered Development</span>
  - Prompting and template selection
  - Project scaffolding
  - Code generation

- <span class="text-green-300">Development Environment</span>
  - StackBlitz setup
  - Live preview
  - Basic customizations

</div>

<div>

### <span class="text-yellow-300">Deployment & Control</span>

- <span class="text-purple-300">Version Control</span>
  - GitHub basics
  - Repository setup
  - Basic workflow

- <span class="text-pink-300">Deployment Process</span>
  - Netlify setup
  - Domain configuration
  - Deploy settings

</div>
</div>

---
layout: center
background: 'linear-gradient(to right bottom, #2a1f3d, #2d2047, #302151, #32225b, #342365)'
class: 'text-white'
---

# <span class="text-gray-400">Topics for Another Day...</span>

<div class="mt-8 flex flex-wrap justify-center gap-4">
  <span class="px-4 py-2 bg-blue-500/20 rounded-full text-blue-300 hover:bg-blue-500/30 transition-colors">Advanced Testing</span>
  <span class="px-4 py-2 bg-green-500/20 rounded-full text-green-300 hover:bg-green-500/30 transition-colors">GitHub Actions</span>
  <span class="px-4 py-2 bg-purple-500/20 rounded-full text-purple-300 hover:bg-purple-500/30 transition-colors">Advanced Netlify Features</span>
  <span class="px-4 py-2 bg-pink-500/20 rounded-full text-pink-300 hover:bg-pink-500/30 transition-colors">Database Design</span>
  <span class="px-4 py-2 bg-yellow-500/20 rounded-full text-yellow-300 hover:bg-yellow-500/30 transition-colors">Security</span>
  <span class="px-4 py-2 bg-blue-500/20 rounded-full text-blue-300 hover:bg-blue-500/30 transition-colors">Modern Tech Stacks</span>
  <span class="px-4 py-2 bg-green-500/20 rounded-full text-green-300 hover:bg-green-500/30 transition-colors">Performance Optimization</span>
  <span class="px-4 py-2 bg-purple-500/20 rounded-full text-purple-300 hover:bg-purple-500/30 transition-colors">API Architecture</span>
</div>

<div class="mt-8 text-gray-400 text-sm">
  Don't worry! We'll focus on the essentials today.
</div>

---
layout: default
background: 'linear-gradient(to right bottom, #2a1f3d, #2d2047, #302151, #32225b, #342365)'
class: 'text-white'
---

# Workshop Timeline

<div class="mb-8">
```mermaid
graph LR
    A[bolt.new] -->|Generate App| B[StackBlitz]
    B -->|Edit & Preview| C[GitHub]
    C -->|Version Control| D[Netlify]
    D -->|Deploy| E[Live Site]
    style A fill:#4F46E5,stroke:#4F46E5,color:white
    style B fill:#0EA5E9,stroke:#0EA5E9,color:white
    style C fill:#22C55E,stroke:#22C55E,color:white
    style D fill:#EC4899,stroke:#EC4899,color:white
    style E fill:#EAB308,stroke:#EAB308,color:white
```
</div>

<div class="grid grid-cols-3 gap-8">
<div>

### <span class="text-yellow-300">Hour 1</span>
- <span class="text-blue-300">AI Development Basics</span>
- <span class="text-green-300">Project Setup</span>
- <span class="text-purple-300">Code Generation</span>

</div>

<div>

### <span class="text-yellow-300">Hour 2</span>
- <span class="text-blue-300">GitHub Integration</span>
- <span class="text-green-300">StackBlitz Setup</span>
- <span class="text-purple-300">Development Flow</span>

</div>

<div>

### <span class="text-yellow-300">Hour 3</span>
- <span class="text-blue-300">Netlify Deployment</span>
- <span class="text-green-300">Best Practices</span>
- <span class="text-purple-300">Next Steps</span>

</div>
</div>

<div class="mt-8 text-center text-gray-400">
  Each section includes hands-on practice and interactive Q&A
</div>

---
layout: default
background: 'linear-gradient(to right bottom, #2a1f3d, #2d2047, #302151, #32225b, #342365)'
class: 'text-white'
---

# Example Projects

<div class="grid grid-cols-2 gap-8">
<div>

### <span class="text-yellow-300">Business Solutions</span>
<div class="mt-4">
  <a href="https://vandevercollective.com/" target="_blank" class="block p-4 bg-white/5 rounded-lg hover:bg-white/10 transition-colors">
    <h4 class="text-blue-300 text-lg mb-2">Vandever Collective</h4>
    <p class="text-gray-300">Professional business website with modern design and AI integration</p>
  </a>
</div>

### <span class="text-yellow-300">AI Applications</span>
<div class="mt-4">
  <a href="https://pocket-somm.netlify.app/" target="_blank" class="block p-4 bg-white/5 rounded-lg hover:bg-white/10 transition-colors">
    <h4 class="text-green-300 text-lg mb-2">Pocket Sommelier</h4>
    <p class="text-gray-300">AI-powered wine recommendation system</p>
  </a>
</div>

</div>

<div>

### <span class="text-yellow-300">Analysis Tools</span>
<div class="mt-4">
  <a href="https://scintillating-banoffee-9c2440.netlify.app/" target="_blank" class="block p-4 bg-white/5 rounded-lg hover:bg-white/10 transition-colors">
    <h4 class="text-purple-300 text-lg mb-2">Comment Analysis</h4>
    <p class="text-gray-300">AI-driven comment sentiment analysis tool</p>
  </a>
</div>

### <span class="text-yellow-300">Migration Examples</span>
<div class="mt-4">
  <a href="https://color-analysis-migration.netlify.app/" target="_blank" class="block p-4 bg-white/5 rounded-lg hover:bg-white/10 transition-colors">
    <h4 class="text-pink-300 text-lg mb-2">Color Analysis</h4>
    <p class="text-gray-300">Demonstration of successful platform migration</p>
  </a>
</div>

</div>
</div>

<div class="mt-8 text-center text-gray-400">
  All examples built using the tools and techniques we'll cover today
</div>

---
layout: center
class: text-center
background: 'linear-gradient(to right bottom, #2a1f3d, #2d2047, #302151, #32225b, #342365)'
---

# Let's Start Building! 🚀

<div class="mt-12">
<h3 class="text-2xl text-blue-300 mb-4">Time to Put Theory into Practice</h3>

<div class="text-xl text-gray-300">
Head over to <a href="https://bolt.new" target="_blank" class="text-blue-300 hover:text-blue-400">bolt.new</a> to start building your own AI-powered web application!
</div>

<div class="mt-8 flex justify-center gap-4">
  <div class="px-6 py-3 bg-blue-500/20 rounded-lg text-blue-300">
    <carbon:code class="inline-block mr-2"/> Write Code
  </div>
  <div class="px-6 py-3 bg-green-500/20 rounded-lg text-green-300">
    <carbon:development class="inline-block mr-2"/> Build Features
  </div>
  <div class="px-6 py-3 bg-purple-500/20 rounded-lg text-purple-300">
    <carbon:deploy class="inline-block mr-2"/> Deploy Live
  </div>
</div>
</div>