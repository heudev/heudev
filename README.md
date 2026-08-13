```javascript
"use creativity";
import { Person } from "türkiye/izmir";

const enes = new Person({
  name: "Enes Uysal",
  title: "Software Engineer",
  email: "enes@enes.run",
  website: "https://enes.run",
  cv: "https://cv.enes.run",
});

enes.links = {
  linkedin: "https://linkedin.enes.run",
  instagram: "https://instagram.enes.run",
  spotify: "https://spotify.enes.run",
};

enes.showcase = [
  { url: "https://forum.ieu.app",    what: "Community platform for İzmir University of Economics · 8,000+ members" },
  { url: "https://ieu.app",          what: "Course timetable generator · used by nearly the entire university" },
  { url: "https://timetabler.app",   what: "Timetable planning · generalized for any university" },
  { url: "https://msku.org",         what: "Community platform for Muğla Sıtkı Koçman University" },
  { url: "https://dokuzeylul.net",   what: "Community platform for Dokuz Eylül University" },
  { url: "https://ege.uniforum.app", what: "Community platform for Ege University" },
  { url: "https://dersanalizi.com",  what: "Transcript-based graduation planning · students across Türkiye" },
];

enes.currently = [
  "Building AI-powered exam evaluation software @ IEU Faculty of Engineering",
  "Developing an LMS platform with workflow automations @ Campus Global",
];

enes.stack = {
  languages: ["JavaScript", "TypeScript"],
  frontend:  ["React", "Next.js", "Tailwind", "Electron"],
  backend:   ["Node.js", "Express", "MongoDB", "Firebase"],
  devops:    ["Docker", "GCP", "Selenium", "Git"],
};

enes.recharge = () => listen("blues") && play("guitar");

export default enes;
```
