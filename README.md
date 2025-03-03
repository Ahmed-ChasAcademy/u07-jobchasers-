1. Allmänt om ramverket React: Hur/Varför uppkom det? Vad är centralt i React?
React skapades av Facebook 2012 för att bygga webbappar snabbare med en komponentbaserad struktur. Komponenter och ett effektivt sätt att hantera UI-uppdateringar är kärnan i React.

2. Vad är JSX?
JSX är ett syntax-tillägg för JavaScript som låter dig skriva HTML-liknande kod inuti JavaScript.

3. Vad är en komponent?
En komponent är en återanvändbar bit kod (UI + logik) som kan vara antingen en funktion eller en klass.

4. Vad är props?
Props används för att skicka data från en förälder till en barnkomponent. De är skrivskyddade.

5. Vad menas med one-way-dataflow?
Data i React flödar bara åt ett håll – från förälder till barn via props. Det gör applikationen mer förutsägbar.

6. Hur kan man använda sig av konditionell rendering i React?
Med if-satser, ternary operators (? :) eller logisk AND (&&) i JSX.

7. Vad menas med en återanvändbar komponent?
En komponent som kan användas på flera ställen i en app utan att duplicera kod.

8. Vad är state i React?
State är komponentens egna, föränderliga data som påverkar dess rendering.

9. Vad är det för skillnad mellan state och props?
State ändras inuti komponenten, medan props kommer utifrån och är oföränderliga.

10. Vad menas med en kontrollerad komponent i React?
En input där React hanterar dess värde genom state, istället för att låta DOM:en göra det.

11. Vad är en callback handler?
En funktion som skickas som prop till en komponent och körs vid en händelse (t.ex. klick).

12. Vad menas med "lifting state up"?
När state flyttas uppåt i komponentträdet för att delas mellan flera komponenter.

13. Vad är syftet med useEffect-hook i React?
För att hantera sidoeffekter, som API-anrop eller manipulering av DOM.

14. Vad är syftet kring den s.k dependency-arrayen i useEffect?
Den styr när effekten ska köras – tom array ([]) betyder en gång, och med beroenden körs effekten när de ändras.

15. Vilka fördelar finns det med att använda NextJS? Nackdelar?
Fördelar: Server-side rendering, bättre SEO, snabbare prestanda.
Nackdelar: Lite mer komplexitet jämfört med vanlig React.

16. Vad menas med Routing? På vilket sätt löser NextJS Routing v.s "vanliga React"?
Routing styr hur sidor byts ut. React använder react-router, medan Next.js har inbyggd filbaserad routing.

17. Vad menas med Reacts ekosystem? Nämn några viktiga bibliotek i Reacts ekosystem?
Alla verktyg och bibliotek runt React, t.ex. React Router, Redux, Zustand och Tailwind.

18. Vad är syftet med useContext? Vilket problem med props löser den?
useContext delar data mellan komponenter utan att props behöver skickas genom flera nivåer.

19. Vad är Redux Toolkit?
Ett enklare och mer effektivt sätt att använda Redux för global state management.

20. När, i vilka situationer vill man använda Redux Toolkit?
När appen har mycket delad state, t.ex. autentisering eller komplexa API-anrop.