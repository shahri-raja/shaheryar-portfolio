Next.js

- Three.js
- Framer Motion
- Tailwind CSS

## <a name="features"> Features</a>

**Hero**: Captivating introduction featuring a spotlight effect and dynamic background.

**Bento Grid**: Modern layout presenting personal information using cutting-edge CSS design techniques.

**3D Elements**: Interactive 3D design elements, such as a GitHub-style globe and card hover effects, adding depth and engagement.

**Testimonials**: Dynamic testimonials area with scrolling or animated content for enhanced engagement.

**Work Experience**: Prominent display of professional background for emphasis and credibility.

**Canvas Effect**: Innovative use of HTML5 canvas to create visually striking effects in the "approaches" section.

**Responsiveness**: Seamless adaptability across all devices, ensuring optimal viewing experience for every user.

and many more, including code architecture and reusability

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

 <details>
 <summary><code>data/index.ts</code></summary>
 
 ```typescript
 export const navItems = [
   { name: "About", link: "#about" },
   { name: "Projects", link: "#projects" },
   { name: "Testimonials", link: "#testimonials" },
   { name: "Contact", link: "#contact" },
 ];
 
 export const gridItems = [
   {
     id: 1,
     title: "I prioritize client collaboration, fostering open communication ",
     description: "",
     className: "lg:col-span-3 md:col-span-6 md:row-span-4 lg:min-h-[60vh]",
     imgClassName: "w-full h-full",
     titleClassName: "justify-end",
     img: "/b1.svg",
     spareImg: "",
   },
   {
     id: 2,
     title: "I'm very flexible with time zone communications",
     description: "",
     className: "lg:col-span-2 md:col-span-3 md:row-span-2",
     imgClassName: "",
     titleClassName: "justify-start",
     img: "",
     spareImg: "",
   },
   {
     id: 3,
     title: "My tech stack",
     description: "I constantly try to improve",
     className: "lg:col-span-2 md:col-span-3 md:row-span-2",
     imgClassName: "",
     titleClassName: "justify-center",
     img: "",
     spareImg: "",
   },
   {
     id: 4,
     title: "Tech enthusiast with a passion for development.",
     description: "",
     className: "lg:col-span-2 md:col-span-3 md:row-span-1",
     imgClassName: "",
     titleClassName: "justify-start",
     img: "/grid.svg",
     spareImg: "/b4.svg",
   },
 
   {
     id: 5,
     title: "Currently building a JS Animation library",
     description: "The Inside Scoop",
     className: "md:col-span-3 md:row-span-2",
     imgClassName: "absolute right-0 bottom-0 md:w-96 w-60",
     titleClassName: "justify-center md:justify-start lg:justify-center",
     img: "/b5.svg",
     spareImg: "/grid.svg",
   },
   {
     id: 6,
     title: "Do you want to start a project together?",
     description: "",
     className: "lg:col-span-2 md:col-span-3 md:row-span-1",
     imgClassName: "",
     titleClassName: "justify-center md:max-w-full max-w-60 text-center",
     img: "",
     spareImg: "",
   },
 ];
 
 export const navItems = [
   { name: "About", link: "#about" },
   { name: "Projects", link: "#projects" },
   { name: "Testimonials", link: "#testimonials" },
   { name: "Contact", link: "#contact" },
 ];
 
 export const gridItems = [
   {
     id: 1,
     title: "I prioritize client collaboration, fostering open communication ",
     description: "",
     className: "lg:col-span-3 md:col-span-6 md:row-span-4 lg:min-h-[60vh]",
     imgClassName: "w-full h-full",
     titleClassName: "justify-end",
     img: "/b1.svg",
     spareImg: "",
   },
   {
     id: 2,
     title: "I'm very flexible with time zone communications",
     description: "",
     className: "lg:col-span-2 md:col-span-3 md:row-span-2",
     imgClassName: "",
     titleClassName: "justify-start",
     img: "",
     spareImg: "",
   },
   {
     id: 3,
     title: "My tech stack",
     description: "I constantly try to improve",
     className: "lg:col-span-2 md:col-span-3 md:row-span-2",
     imgClassName: "",
     titleClassName: "justify-center",
     img: "",
     spareImg: "",
   },
   {
     id: 4,
     title: "Tech enthusiast with a passion for development.",
     description: "",
     className: "lg:col-span-2 md:col-span-3 md:row-span-1",
     imgClassName: "",
     titleClassName: "justify-start",
     img: "/grid.svg",
     spareImg: "/b4.svg",
   },
 
   {
     id: 5,
     title: "Currently building a JS Animation library",
     description: "The Inside Scoop",
     className: "md:col-span-3 md:row-span-2",
     imgClassName: "absolute right-0 bottom-0 md:w-96 w-60",
     titleClassName: "justify-center md:justify-start lg:justify-center",
     img: "/b5.svg",
     spareImg: "/grid.svg",
   },
   {
     id: 6,
     title: "Do you want to start a project together?",
     description: "",
     className: "lg:col-span-2 md:col-span-3 md:row-span-1",
     imgClassName: "",
     titleClassName: "justify-center md:max-w-full max-w-60 text-center",
     img: "",
     spareImg: "",
   },
 ];
 
 export const projects = [
   {
     id: 1,
     title: "Remote Madican Care (Web Application)",
     des: "Remote Medical Care telehealth platform, designed to offer comprehensive healthcare services. The platform enables video calls, live chat, and remote medical testing through IoT device integration. It supports AI diagnosis, appointment scheduling, and secure medical record storage.",
     img: "/p1.jpg",
     iconLists: ["/re.svg", "/java.svg", "/html.svg", "/tail.svg", "/xd.svg"],
     link: "https://care.remotemedtech.com/",
   },
   {
     id: 2,
     title: "Fund Imapact (Web Application)",
     des: " Fund Impact is a web-based funding platform designed to empower creators by connecting them with supporters willing to fund impactful projects. As digital platform reshape the funding landscape, “fund Impact” plays a vital role by facilitating community involvement & fostering creativity",
     img: "/p2.jpg",
     iconLists: ["/next.svg", "/java.svg", "/html.svg", "/css.svg", "/xd.svg"],
     link: "https://fund-impact.vercel.app/",
   },
   {
     id: 3,
     title: "SB Cosmetics (Online Shopping Website)",
     des: "SB cosmetics is a online shopping plateform that offer the customers a variety of the latest Cosmetics & Beauty Products.SB Cosmetics have come a long way, so  Cosmetics know exactly which direction to take when supplying you with high quality yet budget-friendly products.SB cosmetics offer all of this while providing excellent customer service and friendly support.",
     img: "/p3.jpg",
     iconLists: [
       "/java.svg",
       "/html.svg",
       "/css.svg",
       "/xd.svg",
       "/illustrator.svg",
     ],
     link: "https://sufyanbashirllc.com/",
   },
   {
     id: 4,
     title: "Urban Engineers (Web Application)",
     des: "Urban Engineers is MEP specialist with core expertise in centralized Heating, Ventilation & Air Conditioning (HVAC) Systems. The company established in 2017 as a registered partnership. However, the founders were in HVAC business since 2003. We have diverse expertise in commercial and industrial MEP systems. We believe in providing the most energy efficient and reliable MEP systems with an installation that has ease of operation and maintenance",
     img: "/p4.jpg",
     iconLists: [
       "/html.svg",
       "/css.svg",
       "/java.svg",
       "/xd.svg",
       "/illustrator.svg",
     ],
     link: "https://urbanengr.com/",
   },
 ];
 
 export const testimonials = [
   {
     quote:
       "Working with Shaheryar Ahmed  on our products was a game-changer. He has an incredible ability to step into the user's shoes and create experiences that feel effortless. His attention to detail and empathy-driven design elevated our platform beyond expectations. He consistently delivered intuitive wireframes and prototypes that streamlined our decision-making process. I'd trust him with any user-facing product, no matter how complex.",
     name: "Ahmed Hashmi",
     title: "Product Manager at NWBC",
   },
   {
     quote:
       "Shaheryar Ahmed brought our front-end clean, efficient code and a deep understanding of modern frameworks. He doesn't just build interfaces but he crafts fast, responsive, and engaging user journeys. We couldn't have asked for a more reliable developer. Communication was seamless throughout, and he was always ahead of deadlines. His proactive suggestions even helped us improve our performance scores significantly.",
     name: "Fahad Nisar",
     title: "Senior Software Engineer at MAYIMTECH",
   },
   {
     quote:
       "What impressed me most about Shaheryar Ahmed was his ability to dissect complex problems and find smart, scalable solutions. He doesn't just patch things — he understands them. His analytical mindset was a major asset to our project's success. He often uncovered issues before they became real problems, saving us both time and resources. His calm, methodical approach raised the bar for our entire team.",
     name: "Abdus Sami khan",
     title: "project Manager at MAYIMTECH",
   },
   {
     quote:
       "From the first mockup to the final asset, Shaheryar Ahmed's design work was consistently sharp, modern, and aligned perfectly with our brand. His visual storytelling helped us connect with our users on a whole new level. He has a true gift for turning abstract ideas into stunning visuals. We constantly received compliments on the interface and it's all thanks to his creative direction. He's an asset to any design-led team.",
     name: "Shuja Abbasi",
     title: "Creative Director at IP-SEC",
   },
   {
     quote:
       "There were moments in our project where we hit roadblocks — and Shaheryar Ahmed was always the one who calmly stepped in with solutions. He's not just a developer; he's a true problem solver who brings clarity and direction when it's needed most. He consistently took ownership of the toughest challenges and delivered results. His resourcefulness and calm under pressure made him indispensable. I'd work with him again in a heartbeat.",
     name: "Aqwas Farooq",
     title: "Project Lead at Airport Travels LTD",
   },
 ];
 
 export const companies = [
   {
     id: 1,
     name: "React native",
     img: "/reactt.svg",
   },
   {
     id: 2,
     name: "JavaScript",
     img: "/jss.svg",
   },
   {
     id: 3,
     name: "HTML-5",
     img: "/htmll.svg",
   },
   {
     id: 4,
     name: "CSS",
     img: "/csss.svg",
   },
   {
     id: 5,
     name: "Adobe XD",
     img: "/xdd.svg",
   },
 ];
 
 export const workExperience = [
   {
     id: 1,
     title: "Frontend Developer Intern",
     desc: "Contributed to building responsive web interfaces, fixing UI bugs, and enhancing component reusability using React during a fast-paced internship program.",
     className: "md:col-span-2",
     thumbnail: "/exp1.svg",
   },
   {
     id: 2,
     title: "UI/UX Designer",
     desc: "Designed intuitive user flows, wireframes, and high-fidelity prototypes to elevate the usability and visual appeal of web and mobile applications.",
     className: "md:col-span-2", // change to md:col-span-2
     thumbnail: "/exp2.svg",
   },
   {
     id: 3,
     title: "Freelance Web Application Projects",
     desc: "Developed a custom web application from scratch for a client, handling everything from UX design to frontend development and deployment.",
     className: "md:col-span-2", // change to md:col-span-2
     thumbnail: "/exp3.svg",
   },
   {
     id: 4,
     title: "Lead Frontend Developer",
     desc: "Led a team of frontend devs to architect and deliver scalable, high-performance features using modern JavaScript frameworks and design systems.",
     className: "md:col-span-2",
     thumbnail: "/exp4.svg",
   },
 ];
 
 export const socialMedia = [
   {
     id: 1,
     img: "/git.svg",
     link: "https://github.com/shahri-raja",
   },
   {
     id: 2,
     img: "/link.svg",
     link: "https://www.linkedin.com/in/shaheryar-ahmed-103967263?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app",
   },
   {
     id: 3,
     img: "/home.svg",
     link: "https://www.youtube.com",
   },
 ];
 
 <summary><code>tailwind.config.ts</code></summary>
 
 import type { Config } from "tailwindcss";
 
 const svgToDataUri = require("mini-svg-data-uri");
 
 const colors = require("tailwindcss/colors");
 const {
   default: flattenColorPalette,
 } = require("tailwindcss/lib/util/flattenColorPalette");
 
 const config = {
   darkMode: ["class"],
   content: [
     "./pages/**/*.{ts,tsx}",
     "./components/**/*.{ts,tsx}",
     "./app/**/*.{ts,tsx}",
     "./src/**/*.{ts,tsx}",
     "./data/**/*.{ts,tsx}",
   ],
   prefix: "",
   theme: {
     container: {
       center: true,
       padding: "2rem",
       screens: {
         "2xl": "1400px",
       },
     },
     extend: {
       colors: {
         black: {
           DEFAULT: "#000",
           100: "#000319",
           200: "rgba(17, 25, 40, 0.75)",
           300: "rgba(255, 255, 255, 0.125)",
         },
         white: {
           DEFAULT: "#FFF",
           100: "#BEC1DD",
           200: "#C1C2D3",
         },
         blue: {
           "100": "#E4ECFF",
         },
         purple: "#CBACF9",
         border: "hsl(var(--border))",
         input: "hsl(var(--input))",
         ring: "hsl(var(--ring))",
         background: "hsl(var(--background))",
         foreground: "hsl(var(--foreground))",
         primary: {
           DEFAULT: "hsl(var(--primary))",
           foreground: "hsl(var(--primary-foreground))",
         },
         secondary: {
           DEFAULT: "hsl(var(--secondary))",
           foreground: "hsl(var(--secondary-foreground))",
         },
         destructive: {
           DEFAULT: "hsl(var(--destructive))",
           foreground: "hsl(var(--destructive-foreground))",
         },
         muted: {
           DEFAULT: "hsl(var(--muted))",
           foreground: "hsl(var(--muted-foreground))",
         },
         accent: {
           DEFAULT: "hsl(var(--accent))",
           foreground: "hsl(var(--accent-foreground))",
         },
         popover: {
           DEFAULT: "hsl(var(--popover))",
           foreground: "hsl(var(--popover-foreground))",
         },
         card: {
           DEFAULT: "hsl(var(--card))",
           foreground: "hsl(var(--card-foreground))",
         },
       },
       borderRadius: {
         lg: "var(--radius)",
         md: "calc(var(--radius) - 2px)",
         sm: "calc(var(--radius) - 4px)",
       },
       keyframes: {
         "accordion-down": {
           from: { height: "0" },
           to: { height: "var(--radix-accordion-content-height)" },
         },
         "accordion-up": {
           from: { height: "var(--radix-accordion-content-height)" },
           to: { height: "0" },
         },
         spotlight: {
           "0%": {
             opacity: "0",
             transform: "translate(-72%, -62%) scale(0.5)",
           },
           "100%": {
             opacity: "1",
             transform: "translate(-50%,-40%) scale(1)",
           },
         },
         shimmer: {
           from: {
             backgroundPosition: "0 0",
           },
           to: {
             backgroundPosition: "-200% 0",
           },
         },
         moveHorizontal: {
           "0%": {
             transform: "translateX(-50%) translateY(-10%)",
           },
           "50%": {
             transform: "translateX(50%) translateY(10%)",
           },
           "100%": {
             transform: "translateX(-50%) translateY(-10%)",
           },
         },
         moveInCircle: {
           "0%": {
             transform: "rotate(0deg)",
           },
           "50%": {
             transform: "rotate(180deg)",
           },
           "100%": {
             transform: "rotate(360deg)",
           },
         },
         moveVertical: {
           "0%": {
             transform: "translateY(-50%)",
           },
           "50%": {
             transform: "translateY(50%)",
           },
           "100%": {
             transform: "translateY(-50%)",
           },
         },
         scroll: {
           to: {
             transform: "translate(calc(-50% - 0.5rem))",
           },
         },
       },
       animation: {
         "accordion-down": "accordion-down 0.2s ease-out",
         "accordion-up": "accordion-up 0.2s ease-out",
         spotlight: "spotlight 2s ease .75s 1 forwards",
         shimmer: "shimmer 2s linear infinite",
         first: "moveVertical 30s ease infinite",
         second: "moveInCircle 20s reverse infinite",
         third: "moveInCircle 40s linear infinite",
         fourth: "moveHorizontal 40s ease infinite",
         fifth: "moveInCircle 20s ease infinite",
         scroll:
           "scroll var(--animation-duration, 40s) var(--animation-direction, forwards) linear infinite",
       },
     },
   },
   plugins: [
     require("tailwindcss-animate"),
     addVariablesForColors,
     function ({ matchUtilities, theme }: any) {
       matchUtilities(
         {
           "bg-grid": (value: any) => ({
             backgroundImage: `url("${svgToDataUri(
               `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" width="100" height="100" fill="none" stroke="${value}"><path d="M0 .5H31.5V32"/></svg>`
             )}")`,
           }),
           "bg-grid-small": (value: any) => ({
             backgroundImage: `url("${svgToDataUri(
               `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" width="8" height="8" fill="none" stroke="${value}"><path d="M0 .5H31.5V32"/></svg>`
             )}")`,
           }),
           "bg-dot": (value: any) => ({
             backgroundImage: `url("${svgToDataUri(
               `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" width="16" height="16" fill="none"><circle fill="${value}" id="pattern-circle" cx="10" cy="10" r="1.6257413380501518"></circle></svg>`
             )}")`,
           }),
         },
         { values: flattenColorPalette(theme("backgroundColor")), type: "color" }
       );
     },
   ],
 } satisfies Config;
 
 function addVariablesForColors({ addBase, theme }: any) {
   let allColors = flattenColorPalette(theme("colors"));
   let newVars = Object.fromEntries(
     Object.entries(allColors).map(([key, val]) => [`--${key}`, val])
   );
 
   addBase({
     ":root": newVars,
   });
 }
 export default config;
