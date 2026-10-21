<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;height=200&amp;section=header&amp;text=Yashi%20Shah&amp;fontSize=52&amp;fontAlignY=35&amp;animation=fadeIn" width="100%" alt="Yashi Shah" />
<img src="assets/hero.svg" width="100%" alt="Yashi Shah — full stack developer with an agentic AI focus, DJSCE Information Technology, CGPA 8.66. Internship at Twwios, Oscillation 3.0 2nd runner-up, TCS Hackathon, alongside my ASCII portrait." />
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;pause=1000&amp;color=58A6FF&amp;center=true&amp;vCenter=true&amp;width=600&amp;lines=Full+Stack+Developer;Exploring+Agentic+AI;Secure+and+Verifiable+Systems;Ideathon+Runner-Up" width="600" alt="Full stack developer · Exploring agentic AI · Secure and verifiable systems · Ideathon runner-up" />
</p>

<p align="center">
<a href="https://www.linkedin.com/in/shahyashi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn" /></a>
<a href="https://lastminutessdeal.com"><img src="https://img.shields.io/badge/Live-Last%20Minutes%20Deal-238636?style=for-the-badge&amp;logo=react&amp;logoColor=white" alt="Last Minutes Deal" /></a>
<a href="mailto:yashishah176@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email Yashi" /></a>
</p>

## <img src="assets/section-about.svg" width="620" alt="About me" />

<p align="center"><img src="assets/yashi.png" width="220" alt="Yashi Shah" /></p>

I'm a full stack developer in the making, and I'm the kind of person who will happily talk to anyone and try anything new. That curiosity is how I ended up building across the stack: React frontends, FastAPI services and real booking and payment flows. Right now I'm pointing it at **agentic AI**: systems that plan, call tools and take real actions, and how to make sure those actions are safe, verified and traceable.

Here is the short version of what I've done:

- Interned as a **Full Stack Developer at Twwios Technologies** (Jul to Aug 2026): built the customer web app for **lastminutessdeal.com**, with booking and payment flows on top of the company's REST APIs.
- Built **SecureDrone**, where every command is signed and encrypted with **NIST post-quantum cryptography**, and all **4 attack types** I simulated were blocked.
- Built **Guardrail Eval** at the **TCS Hackathon**, an LLM safety evaluator that hit **100% precision** on a held-out set.
- **2nd Runner-Up at the Oscillation 3.0 Ideathon**.
- Currently building an **AI traffic system** with [Akshat](https://github.com/AKSHAT200905).

Open to full stack and AI internships, and always up for a hackathon team or a game of badminton.

### Focus areas

<table>
<tr>
<th align="left">Full stack products</th>
<th align="left">Agentic AI exploration</th>
<th align="left">Secure systems</th>
</tr>
<tr>
<td valign="top">React, Vite, FastAPI, Firebase Auth, REST APIs, payment flows</td>
<td valign="top">Tool use, multi-step workflows, guardrails, evals</td>
<td valign="top">Signed and verified actions, replay protection, audit logs</td>
</tr>
</table>

<img src="assets/divider-matrix.svg" width="100%" alt="" />

## <img src="assets/section-carryover.svg" width="620" alt="Why my work carries over to agents" />

| Practice | Where I've done it | Why it matters for agents |
| :-- | :-- | :-- |
| Signed, verified actions | SecureDrone signs every command with ML-DSA-65 and checks it before it runs | An agent's tool calls should be verified, not just trusted |
| Replay and freshness checks | SecureDrone rejects replayed and stale commands | An old or injected instruction should never run twice |
| Output guardrails | Guardrail Eval flags leaks, unsafe content, bias and hallucinations | Agent output must be checked before it reaches a user or a tool |
| Honest evaluation | Guardrail Eval: precision, recall, F1 and run-to-run diffs | Agents need evals that show where they fail, not just demos |
| Audit logs | SecureDrone streams every blocked attack to a live log | Every agent action should be traceable and reviewable |
| Automated testing | SecureDrone: 33 pytest tests in GitHub Actions | Behaviour changes should be caught before they ship |

This is the lens I bring to agentic AI: an agent is only as useful as it is trustworthy.

## <img src="assets/section-experience.svg" width="620" alt="Experience" />

**Full Stack Developer Intern · Twwios Technologies (Last Minutes Deal)**<br />
Jul 2026 to Aug 2026 · Mumbai

- Built the customer web app for a last-minute hotel, villa and buffet deals platform in React 19 and Vite: 11 routes and about 7,000 lines of code.
- Built end-to-end booking flows for stays and buffets with Cashfree checkout, integrated with the company's REST APIs through Axios.
- Added Google sign-in with Firebase Auth, a persistent multi-currency selector (INR, USD, EUR, GBP), a reviews section and infinite scroll.
- Fixed booking-date, auth and pricing bugs through Git branches and pull requests in a multi-developer team.

<p>
<img src="https://img.shields.io/badge/React-161b22?logo=react" alt="React" />
<img src="https://img.shields.io/badge/Vite-161b22?logo=vite" alt="Vite" />
<img src="https://img.shields.io/badge/Firebase-161b22?logo=firebase" alt="Firebase" />
<img src="https://img.shields.io/badge/REST_APIs-161b22?logo=fastapi" alt="REST APIs" />
<img src="https://img.shields.io/badge/Axios-161b22?logo=axios" alt="Axios" />
<img src="https://img.shields.io/badge/Git-161b22?logo=git" alt="Git" />
</p>

<img src="assets/divider-matrix.svg" width="100%" alt="" />

## <img src="assets/section-projects.svg" width="620" alt="Projects" />

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/yashishah176/SecureDrone"><img src="assets/project-securedrone.svg" width="100%" alt="SecureDrone project metrics" /></a>
<h3>SecureDrone</h3>
<p>Post-quantum drone command and control</p>
<ul><li>Signs every command with ML-DSA-65 and encrypts it with AES-256-GCM under an ML-KEM-768 session key.</li><li>Drone-side checks block replay, tampering, forged signatures and stale commands, shown live in an attack simulator.</li><li>One API for a simulator and a real PX4 drone; about 0.2 ms overhead per command; 33 tests in CI.</li></ul>
<p><code>FastAPI</code> <code>React</code> <code>liboqs</code></p>
<a href="https://github.com/yashishah176/SecureDrone">Explore repository →</a>
</td>
<td width="50%" valign="top">
<a href="https://github.com/yashishah176/Guardrail-Eval"><img src="assets/project-guardrail.svg" width="100%" alt="Guardrail Eval project metrics" /></a>
<h3>Guardrail Eval</h3>
<p>LLM safety evaluator · TCS Hackathon</p>
<ul><li>Flags chatbot replies for data leakage, unsafe content, bias, hallucination and unsupported claims.</li><li>Gives each flag a severity score, an explanation and a redacted rewrite.</li><li>Scored with precision, recall, F1 and confusion matrices: 100% precision, 62% recall on a held-out set.</li></ul>
<p><code>Python</code> <code>FastAPI</code> <code>Evals</code></p>
<a href="https://github.com/yashishah176/Guardrail-Eval">Explore repository →</a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://lastminutessdeal.com"><img src="assets/project-lmd.svg" width="100%" alt="Last Minutes Deal project metrics" /></a>
<h3>Last Minutes Deal</h3>
<p>Live booking platform · Internship</p>
<ul><li>Customer web app for last-minute hotel, villa and buffet deals.</li><li>Search, booking and Cashfree payment flows wired to REST APIs.</li><li>Google sign-in, multi-currency pricing and infinite scroll.</li></ul>
<p><code>React 19</code> <code>Firebase</code></p>
<a href="https://lastminutessdeal.com">Visit live site →</a>
</td>
<td width="50%" valign="top">
<img src="assets/project-traffic.svg" width="100%" alt="AI Traffic System project card" />
<h3>AI Traffic System</h3>
<p>In progress · with Akshat</p>
<ul><li>Detects traffic violations from camera footage.</li><li>Uses live traffic to help signals adapt their timing.</li><li>Computer vision and ML, built as a team.</li></ul>
<p><code>Computer vision</code> <code>ML</code></p>
Repository coming soon
</td>
</tr>
</table>

<sub>Project metrics describe different measures, not a shared ranking. Segments represent attack types, risk categories, routes or modules.</sub>

## <img src="assets/section-achievements.svg" width="620" alt="Achievements" />

- **2nd Runner-Up · Oscillation 3.0 Ideathon**
- **TCS Hackathon**: built Guardrail Eval.
- **Certifications**: Agentic AI and AI Agents · Build an AI Travel Agent App with OpenAI · Data Processing and Optimization with Generative AI · Data Warehousing and Business Intelligence.

<img src="assets/divider-matrix.svg" width="100%" alt="" />

## <img src="assets/section-exploring.svg" width="620" alt="What I'm exploring in agentic AI" />

<img src="assets/agent-flow.svg" width="100%" alt="The agent loop I'm exploring: plan, call a tool, verify, evaluate and log, supported by signed actions, scoped permissions, guardrails and audit logs" />

- Agent architectures: planning, tool use and memory
- Tool calling and MCP servers
- Guardrails and evals for LLM applications
- Secure, permissioned actions for agents that act in the real world

## <img src="assets/section-stack.svg" width="620" alt="Tech stack" />

<p align="center">
<img src="https://skillicons.dev/icons?i=py,js,ts,java,c,html,css,react,fastapi,tailwind&amp;theme=dark&amp;perline=10" alt="Python, JavaScript, TypeScript, Java, C, HTML, CSS, React, FastAPI, Tailwind" /><br />
<img src="https://skillicons.dev/icons?i=vite,firebase,git,github,githubactions,linux,vscode,figma&amp;theme=dark&amp;perline=8" alt="Vite, Firebase, Git, GitHub, GitHub Actions, Linux, VS Code, Figma" />
</p>

| Area | Skills |
| :-- | :-- |
| Languages | Python, JavaScript, TypeScript, Java, C, SQL, HTML/CSS |
| Frameworks & libraries | React, FastAPI, Tailwind CSS, Vite, Firebase, Pydantic |
| Tools | Git, GitHub Actions, pytest, Linux/WSL, VS Code, Figma |
| Other | REST APIs, WebSockets, applied cryptography, NumPy, Pandas, scikit-learn |

## <img src="assets/section-education.svg" width="620" alt="Education and leadership" />

**B.Tech in Information Technology**<br />
Dwarkadas J. Sanghvi College of Engineering (DJSCE), Mumbai<br />
2024 to 2028 · **CGPA 8.66**

| Community | Role | Period |
| :-- | :-- | :-- |
| DJS Trinity (Cultural Committee) | Publicity Co-Committee | Sep 2025 to Jul 2026 |
| DJS E-Cell (Entrepreneurship Cell) | Events Co-Committee | Oct 2024 to Oct 2025 |

<img src="assets/divider-matrix.svg" width="100%" alt="" />

## <img src="assets/section-activity.svg" width="620" alt="Activity" />

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yashishah176/yashishah176/output/github-contribution-grid-snake-dark.svg?v=1" />
<img alt="Animated snake tracing my GitHub contribution calendar" src="https://raw.githubusercontent.com/yashishah176/yashishah176/output/github-contribution-grid-snake.svg?v=1" width="100%" />
</picture>

### Let's connect

Happy to talk about full stack, agentic AI, hackathons, badminton, or whatever new thing I'm into this week.

<p align="center">
<a href="https://www.linkedin.com/in/shahyashi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:yashishah176@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email Yashi" /></a>
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;height=100&amp;section=footer" width="100%" alt="" />
</p>
