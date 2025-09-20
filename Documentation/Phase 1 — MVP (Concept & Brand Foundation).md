Amazing—let’s turn **Phase 1: Concept Development & Brand Foundation** into a crisp, shippable MVP you can execute right away.

Below you’ll get:

1. a step-by-step (SBS) implementation plan for Phase 1,

2. three interlinked landing pages (copy \+ structure) for your goals:

   * **A. Wellness (physiotherapy \+ diet \+ Afro-Cuban dance)**

   * **B. Cultural (Spanish lessons \+ culture/dance for adults & kids \+ art/book project)**

   * **C. Food (Cuban-Polish cuisine; pre-delivery waitlist)**

3. SEO-ready titles/descriptions, CTAs, forms, internal links, and starter schema.

All pages connect to the umbrella **ORI Craft Labs** (**ori-craftlabs.com**).

---

# **Phase 1 — MVP (Concept & Brand Foundation)**

## **Outcomes (by end of Phase 1\)**

* Brand voice \+ visuals locked; simple design system.

* Root site \+ 3 landing pages live with lead capture and clear offers.

* First **workshops scheduled** (dance \+ Spanish \+ kids art); slots open for booking/RSVP.

* **Consult requests** flowing (dietitian/physio), plus **food pilot waitlist** collecting preferences.

* Analytics \+ pixels \+ email automations working.

## **SBS Implementation (2–4 weeks)**

### **Sprint 1 — Brand, Stack, Tracking (Week 1\)**

1. **Brand frame**

   * Umbrella: **ORI Craft Labs**

   * Sub-brands: **ORI Wellness**, **ORI Cultura**, **ORI Cocina** (internal names only; on-page you can keep “Wellness / Culture / Food” for clarity).

   * Colors: keep your green/teal/orange/navy palette.

   * Finalize one logo for Phase 1 (iterate later).

2. **Domain \+ architecture**

   * Root: `https://www.ori-craftlabs.com/`

   * Landing paths:

     * `/wellness` (A)

     * `/culture` (B)

     * `/food` (C)

   * Global header links across all pages; footer repeats cross-links.

3. **Site scaffolding (front-end only now)**

   * Next.js (App Router) \+ Tailwind \+ shadcn/ui (you already have the pattern).

   * Components shared: Navbar, Footer, Section, Card, Dialog/Modal, Input, Badge, Accordion, Tabs, Toast.

   * Create a **mock API** in the FE to simulate form submit success (swap to Supabase later).

4. **Analytics & pixels**

   * GA4 (events: `lead_submit`, `consult_request`, `workshop_rsvp`, `waitlist_join`).

   * Meta pixel, TikTok pixel, LinkedIn Insight tag (you know the drill).

   * Tag Manager for all scripts; use UTM conventions from day 1\.

5. **Email \+ forms**

   * Newsletter list: `ORI-Global`.

   * Interest groups (checkboxes): **Wellness**, **Culture**, **Food**.

   * Autoresponders (3-email mini sequences) per page (copy below).

---

### **Sprint 2 — Offers, Scheduling, Pages (Week 2\)**

1. **Pilot calendar**

   * **Afro-Cuban Dance Intro** (adults) – 2 dates (Poznań studio/room rent).

   * **Spanish Mini-Course 5×30 min (Zoom)** – adults.

   * **Cultura Kids Saturday** (dance \+ story \+ craft) – 2 dates.

   * **Free 20-min Physio Screen (video)** – limited slots.

   * **Dietitian Intro Call (15 min)** – limited slots.

2. **Lead magnets**

   * Wellness: “7-Day Anti-Inflammatory Cuban-Polish Menu (PDF)”.

   * Culture: “Spanish from the Kitchen — 30 words you’ll actually use (PDF)”.

   * Food: “Taste & Tell — Early Tasting Night RSVP”.

3. **Payment stance for Phase 1**

   * Keep workshops **RSVP only** (free or small cash at door) for speed.

   * Selling comes in Phase 2; for now it’s lead capture \+ validation.

4. **Publish pages (copy below)**

   * `/wellness`, `/culture`, `/food` live with **forms** \+ **thank-you toasts**.

   * Set up **calendar invite links** (Google Calendar event links) in confirmation emails.

---

### **Sprint 3 — Ads, Email, Feedback (Weeks 3–4)**

1. **Traffic**

   * IG/TikTok short-form: 3 clips/week (dance, recipe, Spanish tip).

   * Local FB/Meetup posts for Poznań groups.

   * Small test campaigns:

     * Meta Lead (Poznań \+ 20km): “Free 20-min physio screen” & “Afro-Cuban trial”.

     * Google Search: “dietetyk poznań”, “zajęcia salsa poznań”, “kurs hiszpańskiego online krótkie”.

2. **Email sequences (per page)**

   * Day 0: instant confirmation \+ what to expect.

   * Day 2: value email (tip \+ short video).

   * Day 5: reminder \+ “Bring a friend” or bonus download.

3. **Feedback loop**

   * After every RSVP/consult: 2-question form (NPS \+ “what made you sign up?”).

   * Iterate copy/offers based on responses.

---

# **URL & Navigation Model**

* Root: **ori-craftlabs.com**

  * Top nav: **Wellness**, **Culture**, **Food**, **About**, **Contact**

  * Cross-links inside every page:

    * Wellness → Culture (dance/Spanish) & Food (meal plans later)

    * Culture → Wellness (physio-safe dance) & Food (kids-friendly dishes)

    * Food → Wellness (dietitian consult) & Culture (recipes \+ Spanish words)

---

# **Landing Page A — Wellness**

*Path: `/wellness`*

## **SEO**

* **Meta title (≤60):** Wellness in Poznań: Dietitian, Physio & Afro-Cuban Dance | ORI Craft Labs

* **Meta description (≤155):** Personalized diet & physiotherapy with joyful Afro-Cuban movement. Free 20-min screen. Beginner-friendly classes in Poznań \+ online consults.

### **Primary keywords**

dietetyk poznań, fizjoterapia poznań, cuban dance poznań, afro-cuban dance, mobility class poznań, zdrowa dieta kubańska

## **Structure & Copy**

**H1:** Feel better, move freely, enjoy the journey.  
 **Subhead:** Physiotherapy-safe plans, personalized nutrition, and beginner-friendly Afro-Cuban dance—all in one place.

**Hero CTAs**

* **Book free 20-min physio screen** (button → consult modal)

* **Join an Afro-Cuban intro class** (button → RSVP form)

* Secondary text link: “Prefer a dietitian intro? Book 15 minutes.”

**Trust row**

* Led by certified **Physiotherapist & Dietitian**

* **Poznań & online**

* Friendly for **beginners, post-injury, and all ages**

**Section: What you get** (3 cards)

* **Physio & Mobility**  
   Safe screens, posture fixes, home routines.

* **Nutrition that fits real life**  
   Cuban-Polish flavors adapted to your goals.

* **Dance as medicine**  
   Afro-Cuban movement that lifts mood & stamina—no experience needed.

**Section: Programs (Phase 1\)**

* **Free 20-min Physio Screen (video)** – check mobility, get 2 quick wins.

* **Dietitian Intro (15 min)** – goals, constraints, next steps.

* **Afro-Cuban Dance Intro (Poznań)** – beginner class, warm community.

**Lead magnet**  
 “**7-Day Anti-Inflammatory Cuban-Polish Menu** (PDF)” – email form.

**Social proof**  
 Short quotes (add later): “I finally enjoy moving again…” “The menu was tasty and simple…”

**FAQ (Accordion)**

1. Is the dance class okay for beginners? → Yes, fully scaled; physio-led safety.

2. Can you adapt to gluten-free/veg? → Absolutely; specify in the form.

3. Do I need equipment? → No; comfortable shoes/water.

4. Are consults online? → Yes—for screens and diet; in-person possible in Poznań.

**Sticky CTA bar (mobile):** Book Free Screen | Join Dance Intro

**Form fields (2 separate forms)**

* **Consult**: Name, Email\*, Reason (pain/mobility/weight/other), Preferred time.

* **Dance RSVP**: Name, Email\*, Experience (none/beginner/intermediate), Notes.

**Cross-links footer:** “Love music & language? Explore our **Culture** page.” “Curious about our food pilot? Join the **Food** waitlist.”

---

# **Landing Page B — Culture**

*Path: `/culture`*

## **SEO**

* **Meta title:** Spanish Lessons, Culture & Kids Workshops in Poznań | ORI Craft Labs

* **Meta description:** Learn Spanish the fun way. Dance & culture sessions for adults. Kids’ Saturday: stories, movement & art. Join a 5-day mini-course online.

### **Primary keywords**

kurs hiszpańskiego poznań, zajęcia dla dzieci poznań, warsztaty kulturowe, salsa dla początkujących, zajęcia plastyczne dla dzieci poznań

## **Structure & Copy**

**H1:** Culture you can feel—language, rhythm, and art.  
 **Subhead:** Spanish lessons with humor, Cuban dance for all levels, and creative workshops for kids.

**Hero CTAs**

* **Start 5-day Spanish mini-course (free)** (email form)

* **RSVP: Cultura Kids Saturday (Poznań)** (form → pick date)

**Section: For adults (cards)**

* **Spanish that sticks**  
   Bite-size lessons tied to food, music, everyday talk.

* **Afro-Cuban dance basics**  
   Learn steps \+ stories behind the rhythm.

* **Culture nights**  
   Cooking demos, mini-talks, and social dancing.

**Section: For kids & families**

* **Cultura Kids Saturday**  
   90 minutes: story time, simple steps, and an art craft.

* **Art & Book Project**  
   Ongoing sketch-to-storybook club—kids illustrate a short tale set in Cuba & Poland.

**Lead magnet**  
 “**Spanish from the Kitchen – 30 real-life words**” (PDF) – email form.

**FAQ**

1. Are classes beginner-friendly? → Yes—no prior Spanish or dance needed.

2. What age for kids sessions? → 5–11 (we group by age onsite).

3. Do parents stay? → Optional—there’s a parents’ lounge corner.

4. Materials provided? → Yes—art supplies and mini handouts.

**Forms**

* **Spanish mini-course**: Email\*, Level (A0/A1+), Interest (travel/food/dance/work).

* **Kids RSVP**: Parent name, Email\*, Child age, Date, Notes.

**Cross-links footer:** “Want physio-safe dance & nutrition? Visit our **Wellness** page.” “Kids loved the food? Watch for our **Food** pilot.”

---

# **Landing Page C — Food (Pilot Waitlist)**

*Path: `/food`*

## **SEO**

* **Meta title:** Healthy Cuban-Polish Meals in Poznań (Pilot) | ORI Craft Labs

* **Meta description:** Join the tasting waitlist for light, vibrant Cuban-Polish dishes. Dietitian-approved, locally sourced, made for busy Poznań families.

### **Primary keywords**

dieta pudełkowa poznań, zdrowe posiłki, kuchnia kubańska, meal prep poznań, zdrowe jedzenie dostawa poznań

## **Structure & Copy**

**H1:** Cuban sunshine, Polish pantry—healthy meals you’ll crave.  
 **Subhead:** Dietitian-designed, locally sourced. Be first to try our pilot menu in Poznań.

**Hero CTAs**

* **Join the tasting waitlist** (form)

* Secondary: **Host a small tasting at your office** (contact form)

**How it works (3 steps)**

1. **Tell us your tastes** (allergens, spice, veg/omni).

2. **Tasting night** (limited seats, Poznań).

3. **Weekly pre-order** (you choose dishes; we cook fresh).

**Sample pilot dishes (cards)**

* Black beans with Polish groats & citrus salsa (GF/VE option)

* Roast chicken with mojo \+ seasonal beet slaw

* Plantain-carrot bake with herbs (VE)

* Guava-oat energy bars, low sugar

**Lead magnet**  
 “**Flavor Guide: Cuban staples you can buy in Poland** (PDF)” – email form.

**FAQ**

1. Delivery area? → Start with Poznań center \+ nearby zones.

2. Allergens? → Listed; we adapt where possible.

3. Vegetarian/vegan? → Multiple options each week.

4. Pricing? → Pilot pricing shared with waitlist first.

**Form: Waitlist**

* Name, Email\*, City/Area, Diet (omnivore/veg/vegan/GF), Allergens, Spice level (mild/medium/spicy), “I can attend tasting night” (yes/no), Notes.

**Cross-links footer:** “Pair meals with physio-safe movement—see **Wellness**.” “Learn the language behind the dishes—visit **Culture**.”

---

# **Reusable CTAs (buttons)**

* **Book Free Physio Screen** → `/wellness#consult` (modal)

* **Join Afro-Cuban Intro** → `/wellness#dance` (form)

* **Start 5-day Spanish Mini-Course** → `/culture#spanish`

* **RSVP Cultura Kids Saturday** → `/culture#kids`

* **Join Food Waitlist** → `/food#waitlist`

---

# **Email Automations (ready to paste)**

### **Wellness (Free Physio Screen)**

* **D0** — Subject: “You’re in—here’s what to expect”  
   Body: confirmation, simple prep (comfy clothes), 2 quick mobility tips video.

* **D2** — “3 tiny habits: posture, breath, spice”  
   Tip: 3-minute mobility \+ easy anti-inflammatory lunch.

* **D5** — “Your 15-min Dietitian Intro?” \+ bonus 7-Day Menu PDF.

### **Culture (Spanish Mini-Course)**

* **D0** — “¡Hola\! Day 1: greetings from the kitchen” \+ 5 mini phrases.

* **D2** — “Day 3: rhythm & dance vocab” \+ 30-sec step video.

* **D5** — “Day 5: your next step” → invite to adults class or kids Saturday.

### **Food (Waitlist)**

* **D0** — “Welcome to the pilot” \+ short survey link (same fields as form if missing).

* **D2** — “What’s in our pantry?” (Polish-available Cuban staples \+ shopping list).

* **D5** — “Tasting Night Invite” (RSVP pick a date).

---

# **Starter JSON-LD (add to `<head>` on root and adapt per page)**

**Organization (root)**

`{`  
  `"@context": "https://schema.org",`  
  `"@type": "Organization",`  
  `"name": "ORI Craft Labs",`  
  `"url": "https://www.ori-craftlabs.com",`  
  `"sameAs": ["https://instagram.com/yourbrand","https://facebook.com/yourbrand"],`  
  `"logo": "https://www.ori-craftlabs.com/logo.png"`  
`}`

**Event (Afro-Cuban Intro, on /wellness)**

`{`  
  `"@context": "https://schema.org",`  
  `"@type": "Event",`  
  `"name": "Afro-Cuban Dance Intro (Beginner)",`  
  `"eventAttendanceMode": "https://schema.org/OfflineEventAttendanceMode",`  
  `"eventStatus": "https://schema.org/EventScheduled",`  
  `"location": {`  
    `"@type": "Place",`  
    `"name": "Poznań Studio",`  
    `"address": "Poznań, Wielkopolska, Poland"`  
  `},`  
  `"organizer": { "@type": "Organization", "name": "ORI Craft Labs" }`  
`}`

---

# **On-page Keyword Strategy (Polish \+ English mix)**

* **Wellness:** dietetyk poznań, fizjoterapia poznań, afro-cuban dance, mobility class poznań, healthy cuban recipes.

* **Culture:** kurs hiszpańskiego poznań, salsa/rumba dla początkujących, warsztaty dla dzieci poznań, zajęcia plastyczne.

* **Food:** dieta pudełkowa poznań, zdrowe posiłki, kuchnia kubańska, meal prep poznań.

Use keywords naturally in: H1/H2, first paragraph, alt text of hero images (e.g., “Afro-Cuban dance class Poznań”), and FAQs. Avoid keyword stuffing.

---

# **What to build (front-end tasks)**

* **Three routes** `/wellness`, `/culture`, `/food` built with your existing Next.js \+ shadcn patterns.

* **Two forms per page** (see fields above) → mock POST → success toast \+ GA4 event.

* **Schedule modal** (on Wellness) and RSVP pickers (simple select of dates—front-end array).

* **Global footer** with cross-links and newsletter capture.

* **Thank-you page** (or toast \+ email) that nudges to the other two pages.

---

# **KPIs to watch in Phase 1**

* **Lead volume** per page (form starts/completions, by source).

* **Workshop RSVP** count & attendance %.

* **Consult requests** booked.

* **Waitlist size** \+ dietary segmentation.

* **Email open/click** rates for each sequence.

* **Content views** (dance short, Spanish tips).

---

## **Quick copy snippets (for ad/hero variants)**

* **Wellness:** “Physio-safe movement \+ food you’ll love. Free 20-min screen.”

* **Culture:** “Spanish you’ll actually use—through food, music, and stories.”

* **Food:** “Healthy Cuban-Polish meals—join the Poznań tasting waitlist.”

Awesome — here are 4 ready-to-paste Next.js (App Router) pages for your MVP:

/ → Main landing (ORI Craft Labs)

/wellness

/culture

/food

They include forms, a consult modal, and success toasts wired to a mock API (replace later with Supabase). I’m also giving you a tiny mock API file and a consult modal component.

Before pasting:

Install shadcn toast & dialog if you haven’t yet:  
npx shadcn@latest add toast dialog input textarea button select separator card

Ensure you have a Navbar/Footer (or comment those imports out).

1\) src/lib/api.mock.ts

Simple in-memory mock functions you can later swap for Supabase/Stripe.

// src/lib/api.mock.ts  
type Ok \= { ok: true };  
const sleep \= (ms: number) \=\> new Promise((r) \=\> setTimeout(r, ms));

export const demoDates \= {  
  dance: \["Thu 19:00", "Sat 10:30"\],  
  kids: \["Sat 11:00", "Sat 13:00"\],  
  tasting: \["Fri 18:30", "Sun 17:00"\],  
};

const db \= {  
  consults: \[\] as any\[\],  
  rsvps: \[\] as any\[\],  
  waitlist: \[\] as any\[\],  
  newsletter: \[\] as any\[\],  
  office: \[\] as any\[\],  
};

export const api \= {  
  async subscribe(email: string, groups: string\[\] \= \[\]): Promise\<Ok\> {  
    await sleep(400);  
    db.newsletter.push({ email: email.toLowerCase(), groups, at: Date.now() });  
    return { ok: true };  
  },

  async createConsult(payload: {  
    name?: string;  
    email: string;  
    reason?: string;  
    preferredTime?: string;  
  }): Promise\<Ok\> {  
    await sleep(500);  
    db.consults.push({ id: crypto.randomUUID(), ...payload, at: Date.now() });  
    return { ok: true };  
  },

  async rsvpDance(payload: {  
    name: string;  
    email: string;  
    experience?: string;  
    date?: string;  
    notes?: string;  
  }): Promise\<Ok\> {  
    await sleep(450);  
    db.rsvps.push({ type: "dance", ...payload, at: Date.now() });  
    return { ok: true };  
  },

  async spanishMini(payload: {  
    email: string;  
    level?: string;  
    interest?: string;  
  }): Promise\<Ok\> {  
    await sleep(350);  
    db.rsvps.push({ type: "spanish-mini", ...payload, at: Date.now() });  
    return { ok: true };  
  },

  async kidsRsvp(payload: {  
    parentName: string;  
    email: string;  
    childAge: string;  
    date?: string;  
    notes?: string;  
  }): Promise\<Ok\> {  
    await sleep(450);  
    db.rsvps.push({ type: "kids", ...payload, at: Date.now() });  
    return { ok: true };  
  },

  async foodWaitlist(payload: {  
    name: string;  
    email: string;  
    area?: string;  
    diet?: string;  
    allergens?: string;  
    spice?: string;  
    attend?: string;  
    notes?: string;  
  }): Promise\<Ok\> {  
    await sleep(500);  
    db.waitlist.push({ ...payload, at: Date.now() });  
    return { ok: true };  
  },

  async officeTasting(payload: {  
    name: string;  
    email: string;  
    company?: string;  
    message?: string;  
  }): Promise\<Ok\> {  
    await sleep(500);  
    db.office.push({ ...payload, at: Date.now() });  
    return { ok: true };  
  },  
};

// tiny analytics stub (swap to GA4 later)  
export const ga \= {  
  track: (event: string, payload?: Record\<string, any\>) \=\>  
    console.log(\`\[ga\] ${event}\`, payload ?? {}),  
};

2\) src/components/consult-modal.tsx

Schedule-a-consult modal used on the Wellness page and Home.

// src/components/consult-modal.tsx  
"use client";

import \* as React from "react";  
import { api, ga } from "@/lib/api.mock";  
import { Button } from "@/components/ui/button";  
import { Input } from "@/components/ui/input";  
import { Textarea } from "@/components/ui/textarea";  
import {  
  Dialog,  
  DialogTrigger,  
  DialogContent,  
  DialogHeader,  
  DialogTitle,  
} from "@/components/ui/dialog";  
import { useToast } from "@/components/ui/use-toast";

export function ConsultModal({ triggerClass \= "" }: { triggerClass?: string }) {  
  const { toast } \= useToast();  
  const \[open, setOpen\] \= React.useState(false);  
  const \[loading, setLoading\] \= React.useState(false);  
  const \[form, setForm\] \= React.useState({  
    name: "",  
    email: "",  
    reason: "",  
    preferredTime: "",  
  });

  async function submit(e: React.FormEvent) {  
    e.preventDefault();  
    if (\!form.email) {  
      toast({ title: "Email required", variant: "destructive" });  
      return;  
    }  
    try {  
      setLoading(true);  
      await api.createConsult(form);  
      ga.track("consult\_request", { src: "consult-modal" });  
      toast({ title: "Request sent\!", description: "We’ll get back shortly." });  
      setForm({ name: "", email: "", reason: "", preferredTime: "" });  
      setOpen(false);  
    } catch {  
      toast({ title: "Something went wrong", variant: "destructive" });  
    } finally {  
      setLoading(false);  
    }  
  }

  return (  
    \<Dialog open={open} onOpenChange={setOpen}\>  
      \<DialogTrigger asChild\>  
        \<Button className={triggerClass} variant="secondary"\>  
          Schedule a consult  
        \</Button\>  
      \</DialogTrigger\>  
      \<DialogContent id="schedule-consult"\>  
        \<DialogHeader\>  
          \<DialogTitle\>Schedule a consult\</DialogTitle\>  
        \</DialogHeader\>  
        \<form onSubmit={submit} className="grid gap-3"\>  
          \<Input  
            placeholder="Your name"  
            value={form.name}  
            onChange={(e) \=\> setForm({ ...form, name: e.target.value })}  
          /\>  
          \<Input  
            type="email"  
            required  
            placeholder="Email\*"  
            value={form.email}  
            onChange={(e) \=\> setForm({ ...form, email: e.target.value })}  
          /\>  
          \<Input  
            placeholder="Preferred time (e.g. Tue 18:00 CET)"  
            value={form.preferredTime}  
            onChange={(e) \=\> setForm({ ...form, preferredTime: e.target.value })}  
          /\>  
          \<Textarea  
            placeholder="Reason / goals"  
            value={form.reason}  
            onChange={(e) \=\> setForm({ ...form, reason: e.target.value })}  
          /\>  
          \<Button type="submit" disabled={loading}\>  
            {loading ? "Sending…" : "Send request"}  
          \</Button\>  
        \</form\>  
      \</DialogContent\>  
    \</Dialog\>  
  );  
}

3\) Ensure Toaster in layout

Add the shadcn Toaster once.

// src/app/layout.tsx (add near end of \<body\>)  
import { Toaster } from "@/components/ui/toaster";  
// ...  
\<body className="min-h-dvh bg-background text-foreground antialiased"\>  
  {children}  
  \<Toaster /\>  
\</body\>

4\) src/app/page.tsx — Main landing (ORI Craft Labs)

Links to the three microsites; buttons open in new tabs per your rule.

// src/app/page.tsx  
import Link from "next/link";  
import { Navbar } from "@/components/navbar";  
import { Footer } from "@/components/footer";  
import { Button } from "@/components/ui/button";  
import { Input } from "@/components/ui/input";  
import { useToast } from "@/components/ui/use-toast";  
import { api, ga } from "@/lib/api.mock";  
import { ConsultModal } from "@/components/consult-modal";

function NewsletterForm() {  
  const { toast } \= useToast();  
  async function onSubmit(formData: FormData) {  
    const email \= String(formData.get("email") || "").trim();  
    if (\!email) return;  
    await api.subscribe(email, \["global"\]);  
    ga.track("newsletter\_join", { page: "home" });  
    toast({ title: "Subscribed\!", description: "Thanks for joining ORI." });  
  }  
  return (  
    \<form action={onSubmit} className="flex w-full max-w-xl gap-3"\>  
      \<Input name="email" type="email" required placeholder="Enter your email" /\>  
      \<Button type="submit"\>Join newsletter\</Button\>  
    \</form\>  
  );  
}

export default function HomePage() {  
  return (  
    \<\>  
      \<Navbar /\>  
      \<main className="mx-auto max-w-7xl px-4 py-16"\>  
        \<section className="grid items-center gap-8 py-10 md:grid-cols-2"\>  
          \<div className="space-y-6"\>  
            \<h1 className="text-4xl font-extrabold md:text-5xl"\>  
              ORI Craft Labs  
              \<span className="block text-orange-600"\>  
                Wellness • Culture • Food  
              \</span\>  
            \</h1\>  
            \<p className="text-lg text-muted-foreground"\>  
              A Cuban–Polish hub for healthier living: physio-safe movement,  
              real-food nutrition, Spanish & culture workshops, and a tasty  
              meal pilot in Poznań.  
            \</p\>  
            \<div className="flex flex-wrap gap-3"\>  
              \<Button asChild size="lg"\>  
                \<Link href="/wellness" target="\_blank" rel="noopener noreferrer"\>  
                  Explore Wellness  
                \</Link\>  
              \</Button\>  
              \<Button asChild size="lg" variant="outline"\>  
                \<Link href="/culture" target="\_blank" rel="noopener noreferrer"\>  
                  Explore Culture  
                \</Link\>  
              \</Button\>  
              \<Button asChild size="lg" variant="outline"\>  
                \<Link href="/food" target="\_blank" rel="noopener noreferrer"\>  
                  Explore Food  
                \</Link\>  
              \</Button\>  
              \<ConsultModal /\>  
            \</div\>  
            \<div className="pt-2"\>  
              \<NewsletterForm /\>  
            \</div\>  
          \</div\>  
          \<div className="aspect-\[4/3\] rounded-2xl border bg-white/50 shadow-sm" /\>  
        \</section\>

        \<section className="grid gap-6 md:grid-cols-3"\>  
          {\[  
            {  
              title: "Wellness",  
              desc:  
                "Physiotherapy & diet tailored to you, plus Afro-Cuban dance—safe, beginner-friendly, and fun.",  
              href: "/wellness",  
            },  
            {  
              title: "Culture",  
              desc:  
                "Spanish you’ll actually use, dance basics for adults, and creative workshops for kids.",  
              href: "/culture",  
            },  
            {  
              title: "Food",  
              desc:  
                "Healthy Cuban-Polish pilot: join the Poznań tasting waitlist and help shape the menu.",  
              href: "/food",  
            },  
          \].map((c) \=\> (  
            \<div key={c.title} className="rounded-2xl border bg-white/60 p-6 shadow-sm"\>  
              \<h3 className="mb-1 text-xl font-semibold"\>{c.title}\</h3\>  
              \<p className="mb-4 text-sm text-muted-foreground"\>{c.desc}\</p\>  
              \<Button asChild\>  
                \<Link href={c.href} target="\_blank" rel="noopener noreferrer"\>  
                  Visit {c.title}  
                \</Link\>  
              \</Button\>  
            \</div\>  
          ))}  
        \</section\>  
      \</main\>  
      \<Footer /\>  
    \</\>  
  );  
}

5\) src/app/wellness/page.tsx

Forms: Free physio screen (consult modal) and Dance RSVP.

// src/app/wellness/page.tsx  
"use client";

import Link from "next/link";  
import { Navbar } from "@/components/navbar";  
import { Footer } from "@/components/footer";  
import { Button } from "@/components/ui/button";  
import { Input } from "@/components/ui/input";  
import { Textarea } from "@/components/ui/textarea";  
import { Select, SelectContent, SelectItem, SelectTrigger, SelectValue } from "@/components/ui/select";  
import { useToast } from "@/components/ui/use-toast";  
import { api, ga, demoDates } from "@/lib/api.mock";  
import { ConsultModal } from "@/components/consult-modal";  
import { Separator } from "@/components/ui/separator";

export default function WellnessPage() {  
  const { toast } \= useToast();

  async function rsvpDance(formData: FormData) {  
    const payload \= {  
      name: String(formData.get("name") || ""),  
      email: String(formData.get("email") || ""),  
      experience: String(formData.get("experience") || ""),  
      date: String(formData.get("date") || ""),  
      notes: String(formData.get("notes") || ""),  
    };  
    if (\!payload.email || \!payload.name) {  
      toast({ title: "Name & email required", variant: "destructive" });  
      return;  
    }  
    await api.rsvpDance(payload);  
    ga.track("workshop\_rsvp", { type: "dance" });  
    toast({ title: "RSVP confirmed\!", description: "See you in class 🎶" });  
  }

  return (  
    \<\>  
      \<Navbar /\>  
      \<main className="mx-auto max-w-7xl px-4 py-12"\>  
        \<section className="grid items-center gap-8 md:grid-cols-2"\>  
          \<div className="space-y-6"\>  
            \<h1 className="text-4xl font-extrabold md:text-5xl"\>  
              Feel better, move freely, enjoy the journey.  
            \</h1\>  
            \<p className="text-lg text-muted-foreground"\>  
              Physiotherapy screens, personalized nutrition, and beginner-friendly Afro-Cuban dance—led by a certified Physio & Dietitian.  
            \</p\>  
            \<div className="flex flex-wrap gap-3"\>  
              \<ConsultModal /\>  
              \<Button asChild variant="outline"\>  
                \<Link href="\#dance"\>Join Afro-Cuban Intro\</Link\>  
              \</Button\>  
              \<Button asChild variant="ghost"\>  
                \<Link href="/culture" target="\_blank" rel="noopener noreferrer"\>  
                  Prefer Spanish & culture?  
                \</Link\>  
              \</Button\>  
            \</div\>  
          \</div\>  
          \<div className="aspect-\[4/3\] rounded-2xl border bg-white/50 shadow-sm" /\>  
        \</section\>

        \<Separator className="my-10" /\>

        \<section className="grid gap-6 md:grid-cols-3"\>  
          {\[  
            {  
              title: "Physio & Mobility",  
              desc: "Safe screens, posture fixes, and simple home routines.",  
            },  
            {  
              title: "Nutrition that fits life",  
              desc: "Cuban-Polish flavors adapted to your goals.",  
            },  
            {  
              title: "Dance as medicine",  
              desc: "Afro-Cuban movement that lifts mood—no experience needed.",  
            },  
          \].map((c) \=\> (  
            \<div key={c.title} className="rounded-2xl border bg-white/60 p-6 shadow-sm"\>  
              \<h3 className="mb-1 text-lg font-semibold"\>{c.title}\</h3\>  
              \<p className="text-sm text-muted-foreground"\>{c.desc}\</p\>  
            \</div\>  
          ))}  
        \</section\>

        \<section id="dance" className="mt-12 rounded-2xl border bg-white/60 p-6 shadow-sm"\>  
          \<h2 className="mb-2 text-2xl font-bold"\>RSVP: Afro-Cuban Intro (Poznań)\</h2\>  
          \<p className="mb-6 text-muted-foreground"\>  
            Beginner-friendly class; physio-safe pacing. Pick a date and drop your details.  
          \</p\>  
          \<form action={rsvpDance} className="grid gap-4 md:grid-cols-2"\>  
            \<Input name="name" placeholder="Your name" required /\>  
            \<Input name="email" type="email" placeholder="Email" required /\>  
            \<Select name="experience" defaultValue="none"\>  
              \<SelectTrigger className="w-full"\>  
                \<SelectValue placeholder="Experience" /\>  
              \</SelectTrigger\>  
              \<SelectContent\>  
                \<SelectItem value="none"\>No experience\</SelectItem\>  
                \<SelectItem value="beginner"\>Beginner\</SelectItem\>  
                \<SelectItem value="intermediate"\>Intermediate\</SelectItem\>  
              \</SelectContent\>  
            \</Select\>  
            \<Select name="date" defaultValue={demoDates.dance\[0\]}\>  
              \<SelectTrigger className="w-full"\>  
                \<SelectValue placeholder="Date" /\>  
              \</SelectTrigger\>  
              \<SelectContent\>  
                {demoDates.dance.map((d) \=\> (  
                  \<SelectItem key={d} value={d}\>  
                    {d}  
                  \</SelectItem\>  
                ))}  
              \</SelectContent\>  
            \</Select\>  
            \<div className="md:col-span-2"\>  
              \<Textarea name="notes" placeholder="Notes (injuries, requests…)" /\>  
            \</div\>  
            \<div className="md:col-span-2"\>  
              \<Button type="submit"\>Save my spot\</Button\>  
            \</div\>  
          \</form\>  
        \</section\>

        \<section className="mt-10 text-sm text-muted-foreground"\>  
          Looking for language & kids workshops?{" "}  
          \<Link  
            href="/culture"  
            target="\_blank"  
            rel="noopener noreferrer"  
            className="font-medium underline"  
          \>  
            Explore Culture  
          \</Link\>  
        \</section\>  
      \</main\>  
      \<Footer /\>  
    \</\>  
  );  
}

6\) src/app/culture/page.tsx

Forms: Spanish mini-course and Cultura Kids Saturday.

// src/app/culture/page.tsx  
"use client";

import Link from "next/link";  
import { Navbar } from "@/components/navbar";  
import { Footer } from "@/components/footer";  
import { Button } from "@/components/ui/button";  
import { Input } from "@/components/ui/input";  
import { Select, SelectContent, SelectItem, SelectTrigger, SelectValue } from "@/components/ui/select";  
import { Textarea } from "@/components/ui/textarea";  
import { useToast } from "@/components/ui/use-toast";  
import { api, ga, demoDates } from "@/lib/api.mock";  
import { Separator } from "@/components/ui/separator";

export default function CulturePage() {  
  const { toast } \= useToast();

  async function spanishMini(formData: FormData) {  
    const email \= String(formData.get("email") || "");  
    const level \= String(formData.get("level") || "");  
    const interest \= String(formData.get("interest") || "");  
    if (\!email) {  
      toast({ title: "Email required", variant: "destructive" });  
      return;  
    }  
    await api.spanishMini({ email, level, interest });  
    ga.track("spanish\_mini\_join");  
    toast({ title: "¡Listo\!", description: "Check email for Day 1." });  
  }

  async function kidsRsvp(formData: FormData) {  
    const parentName \= String(formData.get("parentName") || "");  
    const email \= String(formData.get("email") || "");  
    const childAge \= String(formData.get("childAge") || "");  
    const date \= String(formData.get("date") || "");  
    const notes \= String(formData.get("notes") || "");  
    if (\!email || \!parentName || \!childAge) {  
      toast({ title: "Parent, email & child age required", variant: "destructive" });  
      return;  
    }  
    await api.kidsRsvp({ parentName, email, childAge, date, notes });  
    ga.track("kids\_rsvp");  
    toast({ title: "RSVP saved\!", description: "See you on Saturday 🎨" });  
  }

  return (  
    \<\>  
      \<Navbar /\>  
      \<main className="mx-auto max-w-7xl px-4 py-12"\>  
        \<section className="grid items-center gap-8 md:grid-cols-2"\>  
          \<div className="space-y-6"\>  
            \<h1 className="text-4xl font-extrabold md:text-5xl"\>  
              Culture you can feel—language, rhythm, and art.  
            \</h1\>  
            \<p className="text-lg text-muted-foreground"\>  
              Spanish that sticks, Afro-Cuban dance for all levels, and creative workshops for kids.  
            \</p\>  
            \<div className="flex flex-wrap gap-3"\>  
              \<Button asChild\>  
                \<Link href="\#spanish"\>Start free Spanish mini-course\</Link\>  
              \</Button\>  
              \<Button asChild variant="outline"\>  
                \<Link href="\#kids"\>RSVP: Cultura Kids Saturday\</Link\>  
              \</Button\>  
              \<Button asChild variant="ghost"\>  
                \<Link href="/wellness" target="\_blank" rel="noopener noreferrer"\>  
                  Looking for physio \+ nutrition?  
                \</Link\>  
              \</Button\>  
            \</div\>  
          \</div\>  
          \<div className="aspect-\[4/3\] rounded-2xl border bg-white/50 shadow-sm" /\>  
        \</section\>

        \<Separator className="my-10" /\>

        \<section id="spanish" className="rounded-2xl border bg-white/60 p-6 shadow-sm"\>  
          \<h2 className="mb-2 text-2xl font-bold"\>Spanish Mini-Course (5 days, email)\</h2\>  
          \<p className="mb-6 text-muted-foreground"\>  
            Bite-size lessons tied to food, music, and everyday talk.  
          \</p\>  
          \<form action={spanishMini} className="grid gap-4 md:grid-cols-3"\>  
            \<Input name="email" type="email" placeholder="Email" required className="md:col-span-2" /\>  
            \<Select name="level" defaultValue="A0"\>  
              \<SelectTrigger\>\<SelectValue placeholder="Level" /\>\</SelectTrigger\>  
              \<SelectContent\>  
                \<SelectItem value="A0"\>A0 (zero)\</SelectItem\>  
                \<SelectItem value="A1"\>A1\</SelectItem\>  
                \<SelectItem value="A2+"\>A2+\</SelectItem\>  
              \</SelectContent\>  
            \</Select\>  
            \<Input name="interest" placeholder="Interest (travel/food/dance/work)" className="md:col-span-3" /\>  
            \<Button type="submit" className="md:col-span-3"\>Send me Day 1\</Button\>  
          \</form\>  
        \</section\>

        \<section id="kids" className="mt-10 rounded-2xl border bg-white/60 p-6 shadow-sm"\>  
          \<h2 className="mb-2 text-2xl font-bold"\>Cultura Kids Saturday (Poznań)\</h2\>  
          \<p className="mb-6 text-muted-foreground"\>  
            90 minutes: story time, simple steps, and an art craft. Materials provided.  
          \</p\>  
          \<form action={kidsRsvp} className="grid gap-4 md:grid-cols-2"\>  
            \<Input name="parentName" placeholder="Parent name" required /\>  
            \<Input name="email" type="email" placeholder="Email" required /\>  
            \<Input name="childAge" placeholder="Child age (e.g. 7)" required /\>  
            \<Select name="date" defaultValue={demoDates.kids\[0\]}\>  
              \<SelectTrigger\>\<SelectValue placeholder="Date" /\>\</SelectTrigger\>  
              \<SelectContent\>  
                {demoDates.kids.map((d) \=\> (  
                  \<SelectItem key={d} value={d}\>{d}\</SelectItem\>  
                ))}  
              \</SelectContent\>  
            \</Select\>  
            \<div className="md:col-span-2"\>  
              \<Textarea name="notes" placeholder="Allergies, preferences…" /\>  
            \</div\>  
            \<div className="md:col-span-2"\>  
              \<Button type="submit"\>Save my spot\</Button\>  
            \</div\>  
          \</form\>  
        \</section\>

        \<section className="mt-10 text-sm text-muted-foreground"\>  
          Hungry already?{" "}  
          \<Link href="/food" target="\_blank" rel="noopener noreferrer" className="font-medium underline"\>  
            Join the Food pilot  
          \</Link\>  
        \</section\>  
      \</main\>  
      \<Footer /\>  
    \</\>  
  );  
}

7\) src/app/food/page.tsx

Forms: Pilot waitlist and Office tasting contact.

// src/app/food/page.tsx  
"use client";

import Link from "next/link";  
import { Navbar } from "@/components/navbar";  
import { Footer } from "@/components/footer";  
import { Button } from "@/components/ui/button";  
import { Input } from "@/components/ui/input";  
import { Textarea } from "@/components/ui/textarea";  
import { Select, SelectContent, SelectItem, SelectTrigger, SelectValue } from "@/components/ui/select";  
import { useToast } from "@/components/ui/use-toast";  
import { api, ga, demoDates } from "@/lib/api.mock";  
import { Separator } from "@/components/ui/separator";

export default function FoodPage() {  
  const { toast } \= useToast();

  async function joinWaitlist(formData: FormData) {  
    const payload \= {  
      name: String(formData.get("name") || ""),  
      email: String(formData.get("email") || ""),  
      area: String(formData.get("area") || ""),  
      diet: String(formData.get("diet") || ""),  
      allergens: String(formData.get("allergens") || ""),  
      spice: String(formData.get("spice") || ""),  
      attend: String(formData.get("attend") || ""),  
      notes: String(formData.get("notes") || ""),  
    };  
    if (\!payload.email || \!payload.name) {  
      toast({ title: "Name & email required", variant: "destructive" });  
      return;  
    }  
    await api.foodWaitlist(payload);  
    ga.track("waitlist\_join", { page: "food" });  
    toast({ title: "You’re on the list\!", description: "We’ll email tasting dates." });  
  }

  async function officeTasting(formData: FormData) {  
    const name \= String(formData.get("name") || "");  
    const email \= String(formData.get("email") || "");  
    const company \= String(formData.get("company") || "");  
    const message \= String(formData.get("message") || "");  
    if (\!email || \!name) {  
      toast({ title: "Name & email required", variant: "destructive" });  
      return;  
    }  
    await api.officeTasting({ name, email, company, message });  
    ga.track("office\_tasting\_contact");  
    toast({ title: "Message sent\!", description: "We’ll coordinate tasting details." });  
  }

  return (  
    \<\>  
      \<Navbar /\>  
      \<main className="mx-auto max-w-7xl px-4 py-12"\>  
        \<section className="grid items-center gap-8 md:grid-cols-2"\>  
          \<div className="space-y-6"\>  
            \<h1 className="text-4xl font-extrabold md:text-5xl"\>  
              Cuban sunshine, Polish pantry—healthy meals you’ll crave.  
            \</h1\>  
            \<p className="text-lg text-muted-foreground"\>  
              Dietitian-designed, locally sourced. Be first to try our pilot menu in Poznań.  
            \</p\>  
            \<div className="flex flex-wrap gap-3"\>  
              \<Button asChild\>\<Link href="\#waitlist"\>Join the tasting waitlist\</Link\>\</Button\>  
              \<Button asChild variant="outline"\>\<Link href="\#office"\>Host an office tasting\</Link\>\</Button\>  
              \<Button asChild variant="ghost"\>  
                \<Link href="/wellness" target="\_blank" rel="noopener noreferrer"\>  
                  Want physio \+ nutrition?  
                \</Link\>  
              \</Button\>  
            \</div\>  
          \</div\>  
          \<div className="aspect-\[4/3\] rounded-2xl border bg-white/50 shadow-sm" /\>  
        \</section\>

        \<Separator className="my-10" /\>

        \<section className="grid gap-6 md:grid-cols-4"\>  
          {\[  
            { t: "Black beans \+ groats \+ citrus salsa", b: "GF • VE option" },  
            { t: "Roast chicken mojo \+ beet slaw", b: "Lean • high protein" },  
            { t: "Plantain-carrot bake with herbs", b: "VE • comfort" },  
            { t: "Guava-oat energy bars", b: "Low sugar" },  
          \].map((x) \=\> (  
            \<div key={x.t} className="rounded-2xl border bg-white/60 p-5 shadow-sm"\>  
              \<h3 className="mb-1 text-base font-semibold"\>{x.t}\</h3\>  
              \<p className="text-sm text-muted-foreground"\>{x.b}\</p\>  
            \</div\>  
          ))}  
        \</section\>

        \<section id="waitlist" className="mt-12 rounded-2xl border bg-white/60 p-6 shadow-sm"\>  
          \<h2 className="mb-2 text-2xl font-bold"\>Join the tasting waitlist\</h2\>  
          \<p className="mb-6 text-muted-foreground"\>  
            Tell us your preferences; we’ll send dates. Limited seats per session.  
          \</p\>  
          \<form action={joinWaitlist} className="grid gap-4 md:grid-cols-2"\>  
            \<Input name="name" placeholder="Your name" required /\>  
            \<Input name="email" type="email" placeholder="Email" required /\>  
            \<Input name="area" placeholder="City/Area (e.g. Poznań Jeżyce)" /\>  
            \<Select name="diet" defaultValue="omnivore"\>  
              \<SelectTrigger\>\<SelectValue placeholder="Diet" /\>\</SelectTrigger\>  
              \<SelectContent\>  
                \<SelectItem value="omnivore"\>Omnivore\</SelectItem\>  
                \<SelectItem value="vegetarian"\>Vegetarian\</SelectItem\>  
                \<SelectItem value="vegan"\>Vegan\</SelectItem\>  
                \<SelectItem value="gluten-free"\>Gluten-free\</SelectItem\>  
              \</SelectContent\>  
            \</Select\>  
            \<Input name="allergens" placeholder="Allergens (comma-separated)" /\>  
            \<Select name="spice" defaultValue="mild"\>  
              \<SelectTrigger\>\<SelectValue placeholder="Spice level" /\>\</SelectTrigger\>  
              \<SelectContent\>  
                \<SelectItem value="mild"\>Mild\</SelectItem\>  
                \<SelectItem value="medium"\>Medium\</SelectItem\>  
                \<SelectItem value="spicy"\>Spicy\</SelectItem\>  
              \</SelectContent\>  
            \</Select\>  
            \<Select name="attend" defaultValue={demoDates.tasting\[0\]}\>  
              \<SelectTrigger\>\<SelectValue placeholder="I can attend…" /\>\</SelectTrigger\>  
              \<SelectContent\>  
                {demoDates.tasting.map((d) \=\> (  
                  \<SelectItem key={d} value={d}\>{d}\</SelectItem\>  
                ))}  
                \<SelectItem value="not-sure"\>Not sure / notify me\</SelectItem\>  
              \</SelectContent\>  
            \</Select\>  
            \<div className="md:col-span-2"\>  
              \<Textarea name="notes" placeholder="Notes (kids friendly? delivery days? …)" /\>  
            \</div\>  
            \<div className="md:col-span-2"\>  
              \<Button type="submit"\>Add me to the list\</Button\>  
            \</div\>  
          \</form\>  
        \</section\>

        \<section id="office" className="mt-10 rounded-2xl border bg-white/60 p-6 shadow-sm"\>  
          \<h2 className="mb-2 text-2xl font-bold"\>Host a small tasting at your office\</h2\>  
          \<p className="mb-6 text-muted-foreground"\>  
            Great for teams and community spaces. We bring samples and a quick food-culture intro.  
          \</p\>  
          \<form action={officeTasting} className="grid gap-4 md:grid-cols-3"\>  
            \<Input name="name" placeholder="Your name" required className="md:col-span-1" /\>  
            \<Input name="email" type="email" placeholder="Email" required className="md:col-span-1" /\>  
            \<Input name="company" placeholder="Company / Venue" className="md:col-span-1" /\>  
            \<Textarea name="message" placeholder="Dates, headcount, notes…" className="md:col-span-3" /\>  
            \<Button type="submit" className="md:col-span-3"\>Send request\</Button\>  
          \</form\>  
        \</section\>

        \<section className="mt-10 text-sm text-muted-foreground"\>  
          Looking for movement & Spanish?{" "}  
          \<Link href="/wellness" target="\_blank" rel="noopener noreferrer" className="font-medium underline"\>  
            Wellness  
          \</Link\>{" "}  
          &{" "}  
          \<Link href="/culture" target="\_blank" rel="noopener noreferrer" className="font-medium underline"\>  
            Culture  
          \</Link\>  
        \</section\>  
      \</main\>  
      \<Footer /\>  
    \</\>  
  );  
}

What’s wired & how to flip live later

Toasts: shadcn useToast \+ \<Toaster /\> in layout.

Mock API: api.mock.ts simulates network \+ stores to memory; swap to real routes later:

/api/subscribe → Supabase early\_access

/api/consult → consult\_requests

/api/rsvp-… → per table

Analytics: ga.track() is a stub; replace with GA4 gtag('event', …) or GTM.

