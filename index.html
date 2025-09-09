import React, { useEffect, useMemo, useState } from "react";
import { motion } from "framer-motion";
import { Mail, Github, Linkedin, Phone, MapPin, ArrowUpRight, Sun, Moon, ExternalLink, Download, ArrowRight } from "lucide-react";

/**
 * Nihan Ali VP – Professional Portfolio (Single-file React Component)
 * ---------------------------------------------------------------
 * ✅ TailwindCSS for styling (UI-friendly, responsive, dark mode)
 * ✅ Framer Motion for subtle animations
 * ✅ Accessible markup + keyboard focus
 * ✅ Sections: Hero, About, Skills, Projects, Certifications, Contact, Footer
 * ✅ SEO-ready content structure (add meta tags in host app's <head>)
 *
 * HOW TO USE
 * 1) Drop this component into any React app (Vite/CRA/Next). Export is default.
 * 2) Ensure Tailwind is configured in the host app.
 * 3) For best SEO, add the meta/OG/JSON-LD we prepared into your index.html or Next <Head>.
 */




const TAGS = {
  frontend: "Frontend",
  backend: "Backend",
  mobile: "Mobile",
  cloud: "Cloud",
  systems: "Systems",
};

// Simple inline SVG logos (no external assets needed)
const Logo = {
  React: () => (
    <svg viewBox="0 0 256 256" className="h-6 w-6" aria-hidden>
      <g fill="none" stroke="currentColor" strokeWidth="14">
        <ellipse cx="128" cy="128" rx="84" ry="32"/>
        <ellipse cx="128" cy="128" rx="84" ry="32" transform="rotate(60,128,128)"/>
        <ellipse cx="128" cy="128" rx="84" ry="32" transform="rotate(120,128,128)"/>
      </g>
      <circle cx="128" cy="128" r="14" fill="currentColor"/>
    </svg>
  ),
  Flutter: () => (
    <svg viewBox="0 0 256 256" className="h-6 w-6" aria-hidden>
      <path fill="currentColor" d="M154 40L38 156l28 28L182 68zM182 188l-28 28-58-58 28-28z"/>
    </svg>
  ),
  Firebase: () => (
    <svg viewBox="0 0 256 256" className="h-6 w-6" aria-hidden>
      <path fill="currentColor" d="M60 200l68 16 68-32-56-104-24 48-16-64z"/>
    </svg>
  ),
  Python: () => (
    <svg viewBox="0 0 256 256" className="h-6 w-6" aria-hidden>
      <path fill="currentColor" d="M96 40h48a40 40 0 0140 40v24H96a24 24 0 01-24-24V64a24 24 0 0124-24zm64 176H112a40 40 0 01-40-40v-24h88a24 24 0 0124 24v16a24 24 0 01-24 24z"/>
      <circle cx="104" cy="72" r="8" fill="#fff"/>
      <circle cx="152" cy="184" r="8" fill="#fff"/>
    </svg>
  ),
  CPP: () => (
    <svg viewBox="0 0 256 256" className="h-6 w-6" aria-hidden>
      <path fill="currentColor" d="M128 24L24 80v96l104 56 104-56V80zM92 164a36 36 0 1136-36H116a20 20 0 10-20 20h64v16z"/>
    </svg>
  ),
  Dart: () => (
    <svg viewBox="0 0 256 256" className="h-6 w-6" aria-hidden>
      <path fill="currentColor" d="M48 72l56-24 88 40 16 56-88 64-72-24z"/>
    </svg>
  ),
  Node: () => (
    <svg viewBox="0 0 256 256" className="h-6 w-6" aria-hidden>
      <path fill="currentColor" d="M128 24l96 56v96l-96 56-96-56V80z"/>
    </svg>
  ),
  Tailwind: () => (
    <svg viewBox="0 0 256 256" className="h-6 w-6" aria-hidden>
      <path fill="currentColor" d="M64 144c16-48 48-72 96-72 24 0 40 8 48 24-16 48-48 72-96 72-24 0-40-8-48-24zm-24-40c16-48 48-72 96-72 24 0 40 8 48 24-16 48-48 72-96 72-24 0-40-8-48-24z"/>
    </svg>
  ),
  Firestore: () => (
    <svg viewBox="0 0 256 256" className="h-6 w-6" aria-hidden>
      <path fill="currentColor" d="M64 48h128v160H64zM88 72h80v16H88zm0 32h80v16H88zm0 32h56v16H88z"/>
    </svg>
  ),
};

const skillsData = [
  { name: "React", level: 90, tag: TAGS.frontend, desc: "SPA, Next.js, Hooks" },
  { name: "Flutter", level: 85, tag: TAGS.mobile, desc: "Web & Mobile UIs" },
  { name: "Firebase", level: 80, tag: TAGS.cloud, desc: "Auth, Firestore, Hosting" },
  { name: "Python", level: 75, tag: TAGS.backend, desc: "FastAPI, Scripting" },
  { name: "C++", level: 70, tag: TAGS.systems, desc: "DSA, Perf" },
  { name: "Dart", level: 70, tag: TAGS.mobile, desc: "Flutter Apps" },
  { name: "Node", level: 72, tag: TAGS.backend, desc: "APIs, Sockets" },
  { name: "Tailwind", level: 88, tag: TAGS.frontend, desc: "Utility-first CSS" },
  { name: "Firestore", level: 82, tag: TAGS.cloud, desc: "Rules, Indexes" },
];

const projects = [
  {
    title: "Workshop Management System",
    blurb:
      "Billing, inventory, salaries & warranty packages. Built with Flutter + Firestore for Web & Mobile.",
    stack: ["Flutter", "Firestore", "Cloud Functions"],
    href: "#",
  },
  {
    title: "EMR System",
    blurb:
      "Smart, secure EMR to empower healthcare pros and improve patient outcomes.",
    stack: ["React", "Tailwind"],
    href: "https://clinicppm.site",
  },
  {
    title: "Realtime Chat",
    blurb: "Minimal chat with rooms & persisted history.",
    stack: ["Node", "Socket.IO"],
    href: "#",
  },
];

const certifications = [
  { name: "Google Developer", verify: "https://g.dev/nihanalivp" },
  { name: "Oracle Java SE 11", verify: "#" },
];

const socials = [
  { label: "GitHub", href: "https://github.com/nihan-ali-vp", Icon: Github },
  { label: "LinkedIn", href: "https://linkedin.com/in/yourhandle", Icon: Linkedin },
  { label: "Email", href: "mailto:qwerty311980@gmail.com", Icon: Mail },
];

function useDarkMode() {
  const [dark, setDark] = useState(() => {
    if (typeof window === "undefined") return false;
    const stored = localStorage.getItem("dark");
    if (stored != null) return stored === "1";
    return window.matchMedia && window.matchMedia("(prefers-color-scheme: dark)").matches;
  });

  useEffect(() => {
    localStorage.setItem("dark", dark ? "1" : "0");
  }, [dark]);

  return { dark, setDark };
}

const Section = ({ id, title, subtitle, children }) => (
  <section id={id} className="scroll-mt-24">
    <div className="flex items-end justify-between mb-4">
      <div>
        <h2 className="text-2xl md:text-3xl font-semibold tracking-tight">{title}</h2>
        {subtitle && (
          <p className="text-sm text-zinc-500 dark:text-zinc-400">{subtitle}</p>
        )}
      </div>
      <a href={`#${id}`} className="text-xs text-zinc-400 hover:text-zinc-600 dark:hover:text-zinc-200">#{id}</a>
    </div>
    {children}
  </section>
);

const Card = ({ children, className = "" }) => (
  <div className={`rounded-2xl bg-white/80 backdrop-blur border border-zinc-200 shadow-sm dark:bg-white/5 dark:border-white/10 ${className}`}>
    {children}
  </div>
);

const Progress = ({ value }) => (
  <div className="h-2 w-full rounded-full bg-zinc-100 dark:bg-white/10 overflow-hidden">
    <div
      className="h-full rounded-full bg-gradient-to-r from-violet-600 to-fuchsia-500"
      style={{ width: `${Math.max(0, Math.min(100, value))}%` }}
    />
  </div>
);

export default function PortfolioSite() {
  const { dark, setDark } = useDarkMode();
  const [filter, setFilter] = useState("All");

  const filteredSkills = useMemo(() => {
    if (filter === "All") return skillsData;
    return skillsData.filter((s) => s.tag === filter);
  }, [filter]);

  return (
    <div className={dark ? "dark" : ""}>
      <div
        className="min-h-screen bg-[radial-gradient(800px_400px_at_10%_10%,rgba(124,58,237,0.08),transparent_25%),radial-gradient(800px_400px_at_90%_90%,rgba(217,70,239,0.06),transparent_25%)] dark:bg-[#0b1020]"
      >
        <div className="mx-auto max-w-6xl px-4 py-6 text-zinc-900 dark:text-zinc-100">
          {/* Header */}
          <header className="flex flex-col gap-3 md:flex-row md:items-center md:justify-between mb-4">
            <div className="flex items-center gap-3">
              <div className="h-12 w-12 rounded-xl bg-gradient-to-br from-violet-600 to-fuchsia-500 text-white font-bold grid place-items-center shadow">
                NA
              </div>
              <div>
                <h1 className="text-lg font-semibold leading-tight">Nihan Ali V P</h1>
                <p className="text-xs text-zinc-500 dark:text-zinc-400">Full-Stack Developer</p>
              </div>
            </div>
            <div className="flex items-center gap-2">
              <a
                href="#"
                onClick={(e) => {
                  e.preventDefault();
                  // Replace with actual resume URL
                  window.open("#", "_blank");
                }}
                className="inline-flex items-center gap-2 rounded-xl border border-zinc-200 bg-white/70 px-3 py-2 text-sm shadow-sm hover:bg-white dark:border-white/10 dark:bg-white/10"
              >
                <Download className="h-4 w-4" /> Resume
              </a>
              <button
                onClick={() => setDark(!dark)}
                className="inline-flex items-center gap-2 rounded-xl border border-zinc-200 bg-white/70 px-3 py-2 text-sm shadow-sm hover:bg-white dark:border-white/10 dark:bg-white/10"
                aria-label="Toggle theme"
                title="Toggle theme"
              >
                {dark ? <Sun className="h-4 w-4" /> : <Moon className="h-4 w-4" />} {dark ? "Light" : "Dark"}
              </button>
            </div>
          </header>

          {/* Hero */}
          <motion.section
            initial={{ opacity: 0, y: 8 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.5 }}
            className="grid grid-cols-1 md:grid-cols-[1fr_320px] gap-4 items-stretch mb-6"
          >
            <Card className="p-5">
              <div className="flex flex-col md:flex-row md:items-center md:justify-between gap-4">
                <div>
                  <span className="inline-flex items-center gap-2 rounded-full bg-zinc-50 px-3 py-1 text-xs text-zinc-600 ring-1 ring-zinc-200 dark:bg-white/5 dark:ring-white/10">
                    <span className="h-2 w-2 rounded-full bg-emerald-500" /> Available for work
                  </span>
                  <h2 className="mt-3 text-2xl md:text-3xl font-semibold">
                    Hi, I’m Nihan Ali V P. <span className="text-zinc-500 dark:text-zinc-400 font-medium">I build clean, fast apps for web & mobile.</span>
                  </h2>
                  <p className="mt-1 text-zinc-600 dark:text-zinc-400">
                    Performance, accessibility and developer experience are my priorities. I enjoy turning ideas into working
                    products.
                  </p>
                  <div className="mt-3 flex flex-wrap gap-2">
                    <a href="#projects" className="inline-flex items-center gap-2 rounded-xl bg-white px-3 py-2 text-sm shadow hover:shadow-md dark:bg-white/10">
                      View Projects <ArrowRight className="h-4 w-4" />
                    </a>
                    <a href="#contact" className="inline-flex items-center gap-2 rounded-xl border border-zinc-200 px-3 py-2 text-sm shadow-sm hover:bg-white/70 dark:border-white/10 dark:hover:bg-white/10">
                      Contact Me
                    </a>
                  </div>
                </div>
                <div className="shrink-0">
                  <Card className="p-0 overflow-hidden">
                    <div className="aspect-[4/3] grid place-items-center text-zinc-400">
                      {/* Replace with real <img src=... alt=... /> */}
                      <div className="text-center">
                        <div className="text-sm font-semibold">N A</div>
                        <div className="text-xs text-zinc-500">Full-Stack • React • Flutter</div>
                      </div>
                    </div>
                  </Card>
                  <div className="mt-3 rounded-xl bg-white/70 p-3 text-sm text-zinc-600 ring-1 ring-zinc-200 dark:bg-white/10 dark:text-zinc-300 dark:ring-white/10">
                    <div className="flex items-center justify-between">
                      <span className="text-xs">Primary</span>
                      <span className="font-medium">React · Flutter · Node</span>
                    </div>
                  </div>
                </div>
              </div>
            </Card>

            <div className="flex flex-col gap-4">
              <Card className="p-4">
                <h3 className="text-center font-semibold">Contact</h3>
                <p className="mt-1 text-center text-sm text-zinc-500 dark:text-zinc-400">qwerty311980@gmail.com</p>
                <div className="mt-2 flex items-center justify-center gap-2">
                  {socials.map(({ label, href, Icon }) => (
                    <a
                      key={label}
                      href={href}
                      target="_blank"
                      rel="noreferrer"
                      className="inline-flex items-center gap-2 rounded-xl border border-zinc-200 px-3 py-2 text-sm shadow-sm transition hover:bg-white/80 dark:border-white/10 dark:hover:bg-white/10"
                      aria-label={label}
                    >
                      <Icon className="h-4 w-4" /> {label}
                    </a>
                  ))}
                </div>
              </Card>
              <Card className="p-4">
                <h4 className="font-semibold mb-1">Quick Info</h4>
                <ul className="text-sm text-zinc-600 dark:text-zinc-300 space-y-2">
                  <li className="flex items-center gap-2"><MapPin className="h-4 w-4"/> Kerala, India</li>
                  <li className="flex items-center gap-2"><Phone className="h-4 w-4"/> +91 •••• •• ••••</li>
                  <li className="flex items-center gap-2"><ExternalLink className="h-4 w-4"/> <a href="#" onClick={(e)=>{e.preventDefault(); window.open('#','_blank')}} className="underline underline-offset-2">Download Resume</a></li>
                </ul>
              </Card>
            </div>
          </motion.section>

          {/* Skills */}
          <Section id="skills" title="Skills" subtitle="What I use to ship"> 
            <div className="flex flex-wrap items-center gap-2 mb-3">
              {(["All", TAGS.frontend, TAGS.backend, TAGS.mobile, TAGS.cloud, TAGS.systems] as const).map((t) => (
                <button
                  key={t}
                  onClick={() => setFilter(t)}
                  className={`rounded-full border px-3 py-1 text-xs transition shadow-sm dark:border-white/10 ${
                    filter === t
                      ? "bg-gradient-to-r from-violet-600 to-fuchsia-500 text-white border-transparent"
                      : "bg-white/70 border-zinc-200 hover:bg-white dark:bg-white/10"
                  }`}
                >
                  {t}
                </button>
              ))}
            </div>

            <div className="grid gap-3 sm:grid-cols-2 lg:grid-cols-3">
              {filteredSkills.map((s, idx) => (
                <motion.div
                  key={s.name}
                  initial={{ opacity: 0, y: 6 }}
                  whileInView={{ opacity: 1, y: 0 }}
                  viewport={{ once: true, margin: "-50px" }}
                  transition={{ duration: 0.35, delay: idx * 0.03 }}
                >
                  <Card className="p-4">
                    <div className="flex items-center justify-between">
                      <div className="flex items-center gap-3">
                        <div className="grid h-10 w-10 place-items-center rounded-lg bg-gradient-to-r from-violet-600 to-fuchsia-500 text-white">
                          {/* Dynamic logo */}
                          {Logo[s.name.replace("+", "P").replace(".", "")] ? (
                            React.createElement(Logo[s.name.replace("+", "P").replace(".", "")])
                          ) : (
                            <span className="text-sm font-semibold">{s.name[0]}</span>
                          )}
                        </div>
                        <div>
                          <div className="font-semibold">{s.name}</div>
                          <div className="text-xs text-zinc-500 dark:text-zinc-400">{s.desc}</div>
                        </div>
                      </div>
                      <span className="text-xs rounded-full bg-zinc-100 px-2 py-1 dark:bg-white/10">{s.tag}</span>
                    </div>
                    <div className="mt-3">
                      <Progress value={s.level} />
                      <div className="mt-1 text-right text-xs text-zinc-500 dark:text-zinc-400">{s.level}%</div>
                    </div>
                  </Card>
                </motion.div>
              ))}
            </div>
          </Section>

          {/* Projects */}
          <Section id="projects" title="Projects" subtitle="Hand‑picked work">
            <div className="grid gap-3 sm:grid-cols-2 lg:grid-cols-3">
              {projects.map((p, idx) => (
                <motion.div key={p.title} initial={{opacity:0,y:6}} whileInView={{opacity:1,y:0}} viewport={{once:true}} transition={{duration:.35, delay: idx*0.04}}>
                  <Card className="p-4 h-full">
                    <h3 className="text-base font-semibold">{p.title}</h3>
                    <p className="mt-1 text-sm text-zinc-600 dark:text-zinc-400">{p.blurb}</p>
                    <div className="mt-2 flex flex-wrap gap-2">
                      {p.stack.map((t) => (
                        <span key={t} className="text-xs rounded-full bg-zinc-100 px-2 py-1 dark:bg-white/10">
                          {t}
                        </span>
                      ))}
                    </div>
                    <div className="mt-3">
                      <a
                        href={p.href}
                        target={p.href?.startsWith("http") ? "_blank" : undefined}
                        rel={p.href?.startsWith("http") ? "noreferrer" : undefined}
                        className="inline-flex items-center gap-2 rounded-xl bg-white px-3 py-2 text-sm shadow hover:shadow-md dark:bg-white/10"
                      >
                        Open <ArrowUpRight className="h-4 w-4" />
                      </a>
                    </div>
                  </Card>
                </motion.div>
              ))}
            </div>
          </Section>

          {/* Certifications */}
          <Section id="certifications" title="Certifications" subtitle="Selected">
            <div className="flex flex-wrap gap-3">
              {certifications.map((c) => (
                <Card key={c.name} className="p-4 flex items-center gap-3 min-w-[260px]">
                  <div className="font-semibold">{c.name}</div>
                  <div className="ml-auto">
                    <a
                      href={c.verify}
                      target={c.verify?.startsWith("http") ? "_blank" : undefined}
                      rel={c.verify?.startsWith("http") ? "noreferrer" : undefined}
                      className="inline-flex items-center gap-2 rounded-xl border border-zinc-200 px-3 py-2 text-sm shadow-sm hover:bg-white/80 dark:border-white/10 dark:hover:bg-white/10"
                    >
                      Verify <ExternalLink className="h-4 w-4" />
                    </a>
                  </div>
                </Card>
              ))}
            </div>
          </Section>

          {/* Contact */}
          <Section id="contact" title="Let’s work together" subtitle="I’m open to freelance & full‑time roles">
            <Card className="p-5">
              <form
                onSubmit={(e) => {
                  e.preventDefault();
                  const form = e.currentTarget;
                  const name = (form.elements.namedItem("name") as HTMLInputElement).value.trim();
                  alert(`Thanks ${name}! This demo form isn't wired yet. Connect to your backend or Formspree.`);
                  form.reset();
                }}
                className="grid gap-3"
              >
                <div className="grid grid-cols-1 sm:grid-cols-2 gap-3">
                  <input
                    name="name"
                    required
                    placeholder="Your name"
                    className="rounded-xl border border-zinc-200 bg-transparent px-3 py-2 text-sm focus:outline-none focus:ring-4 focus:ring-violet-500/10 dark:border-white/10"
                  />
                  <input
                    name="email"
                    type="email"
                    required
                    placeholder="you@example.com"
                    className="rounded-xl border border-zinc-200 bg-transparent px-3 py-2 text-sm focus:outline-none focus:ring-4 focus:ring-violet-500/10 dark:border-white/10"
                  />
                </div>
                <textarea
                  name="message"
                  required
                  placeholder="Tell me about your project or role"
                  className="min-h-[120px] resize-y rounded-xl border border-zinc-200 bg-transparent px-3 py-2 text-sm focus:outline-none focus:ring-4 focus:ring-violet-500/10 dark:border-white/10"
                />
                <div className="flex justify-end">
                  <button
                    type="submit"
                    className="inline-flex items-center gap-2 rounded-xl bg-gradient-to-r from-violet-600 to-fuchsia-500 px-4 py-2 text-sm font-semibold text-white shadow hover:shadow-md"
                  >
                    Send Message <ArrowUpRight className="h-4 w-4" />
                  </button>
                </div>
              </form>
            </Card>
          </Section>

          {/* Footer */}
          <footer className="mt-8 pb-10 text-center text-sm text-zinc-500 dark:text-zinc-400">
            © {new Date().getFullYear()} <span className="font-medium">Nihan Ali V P</span>. All rights reserved.
          </footer>
        </div>
      </div>
    </div>
  );
}
