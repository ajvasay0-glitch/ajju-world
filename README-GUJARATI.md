# Ajju World — Replit Project

આ ZIP માં Ajju World વેબસાઇટનો સંપૂર્ણ source project છે. આ માત્ર HTML ફાઇલ નથી; React/Vite frontend, Express API workspace અને જરૂરી project configuration સામેલ છે.

## Replit માં ચલાવવા
1. ZIP extract કરો અને અંદરનો `Ajju-World` project folder Replit માં upload/import કરો.
2. Replit ને `pnpm` workspace project તરીકે ઓળખવા દો અને dependencies install થવા દો.
3. Project run કરો. Frontend માટે `pnpm --filter @workspace/ajju-world run dev` ઉપયોગમાં આવે છે.
4. Full API/deployment માટે `DATABASE_URL` (PostgreSQL) તથા સંબંધિત secrets જરૂરી પડી શકે છે. AI Image/Assistant માટે provider configuration પણ જરૂરી છે.
5. Build ચકાસવા `pnpm --filter @workspace/ajju-world run build` ચલાવો.

## શું છે
- Responsive Ajju World homepage અને navigation
- Search, video, shopping, education, jobs, news, earning અને information pages
- Education માં ધોરણ 1–12 અને વિષય પસંદગી
- ધોરણ 10 માટે નમૂનાના Gujarati MCQ, answer checking અને score
- Jobs માટે job search તથા India ના official career/recruitment portals ની links
- Language selector અને About/Contact/Privacy/Terms pages

## મહત્વની સ્પષ્ટતા
Education પેજની અંદર જ રહે છે; પણ આ ZIP માં બધા ધોરણો/વિષયોના સંપૂર્ણ પાઠ, નોટ્સ, સ્વાધ્યાય અને મોટી MCQ question bank હજી સામેલ નથી. હાલમાં ધોરણ 10ના થોડા નમૂનાના MCQ છે. ભરતીની છેલ્લી તારીખો માટે live database/API નથી, તેથી apply કરતાં પહેલાં official website પર તારીખ અને eligibility તપાસવી.

## Hosting
Replit નો free availability/limits સમય સાથે બદલાઈ શકે છે. Database/API આધારિત તમામ સુવિધાઓ દરેક static/free host પર આપમેળે ચાલશે નહીં. Replit માં import કર્યા પછી build/run logs ચકાસવા.
