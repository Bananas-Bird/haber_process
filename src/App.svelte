<script lang="ts">
  import svelteLogo from "./assets/svelte.svg";
  import viteLogo from "/vite.svg";

  import MathMl from "svelte-tex/package/MathML.svelte";
</script>

<main>
  <div class="center main">
    <h1>The Catalysts of the Haber process</h1>
    <p>
      The harber process is one of the most important industrial procedures of
      all time. It has been used for fertilizers that feed half the planet,
      along with many other chemical uses such as fertilizers and water
      purification. Ammonia’s use as a fertilizer is primarily dependent on the
      nitrogen inside it. Nitrogen is essential for the human body to function.
      It is used to create amino acids, which create proteins, and is also used
      to create RNA and DNA. For plants, it is used to make chlorophyll, an
      essential component of photosynthesis. Nitrogen is not a rare element; it
      makes up 78% of our atmosphere. But in order for nitrogen to be useful, it
      needs to be in its atomic state—a single lone atom. In its atmospheric
      form, nitrogen is N2, diatomic nitrogen. The problem is that to turn
      diatomic nitrogen into atomic nitrogen requires breaking one of the
      strongest chemical bonds in nature. The energy required to dissociate one
      mole of nitrogen is 964 kilojoules. You could heat 128 moles of water from
      0 to 100 °C using the same amount of energy. For most of history, the
      primary source of nitrogen has been bacteria in soil, which use tremendous
      energy to destroy the n2 bond. Then plants get nitrogen from the soil,
      which is how most of the animal kingdom gets its nitrogen. This was until
      the German chemist Fritz Haber developed the first process for ammonia
      production on an industrial scale.
    </p>
    <p>The chemical equation for ammonia synthesis is as follows.</p>
    <MathMl
      tex={String.raw`N_2 + 3H_2\rightleftharpoons 2NH_3 + 92 + \text{heat}`}
    ></MathMl>
    <p>
      For this we can see that it is an exothermic reversible reaction. This
      means that chemical equilibrium will come into play. Le Chatelier's
      Principle tells us that for exothermic reactions, the chemical equilibrium
      will favor lower temperatures. Meaning that a higher proportion of the
      chemical equilibrium will be products. The problem with this is that at
      lower temperatures the reaction rate will be very slow. So to compromise
      we just have a temperature around 500c, which quickly gives an equilibrium
      mixture of 15% products. Le Chatelier's Principle also tells us that a
      chemical reaction will try to lower its pressure as much as possible, if
      the pressure is increased it will favor the side with less molecules due
      to avogadro's law. For the dissociation of nitrogen, a catalyst can be
      used.
    </p>
    <p>The reaction mechanism for the ammonia synthesis is as follows.</p>
    <ol>
      <li>
        <MathMl tex={String.raw`N_2(g) \rightarrow N_2(absorbed)`}></MathMl>
      </li>
      <li>
        <MathMl tex={String.raw`N_2(absorbed) \rightarrow 2N(absorbed)`}
        ></MathMl>
      </li>
      <li>
        <MathMl tex={String.raw`H_2(g) \rightarrow H_2(adsorbed)`}></MathMl>
      </li>
      <li>
        <MathMl tex={String.raw`H_2(adsorbed) \rightarrow 2H(adsorbed)`}
        ></MathMl>
      </li>
      <li>
        <MathMl
          tex={String.raw`N(adsorbed) + 3H(adsorbed) \rightarrow NH_3(adsorbed)`}
        ></MathMl>
      </li>
      <li>
        <MathMl tex={String.raw`NH_3(adsorbed)\rightarrow NH_3(g)`}></MathMl>
      </li>
    </ol>
    <p>
      It should be no surprise that the fixing of nitrogen, a reaction that
      takes a tremendous amount of energy, is the rate limiting step. To speed
      up the overall reaction, and thus the synthesis of ammonia you need to
      speed up the rate limiting step. This is where a catalyst comes into play.
      When Haber was first developing his process, he used osmium as a catalyst
      which led to his eureka moment. But he was exceptionally lucky. He worked
      for a lightbulb company which had a supply of osmium for experiments. At
      the time there was only 100 kg of osmium in the world. Later Bosch used an
      iron based catalyst. More modern developments have seen ruthenium, based
      catalyst and electrochemical synthesis for the production of ammonia.
    </p>
    <h2>What is a catalyst</h2>
    <p>
      A catalyst derived from the greek word katalύein, meaning "to dissolve",
      it is something that speeds up the rate of reaction. It provides an
      alternative method for the reaction to provide, giving two reactions a
      fast and a slow way to provide. Kind of like finding a faster route to
      return home. If the reaction takes place with the catalyst, the faster
      route will be taken rather than the slow one. It does this by reducing the
      activation energy for the reaction to occur. This allows more molecules to
      undergo the reaction. A catalyst does get used up during the reaction but
      can get poisoned, or deactivated. For example with an iron based catalyst,
      oxygen can bind to the surface of iron and deactivate the catalyst,
      effectively it is a log blocking a road.
    </p>
    <h2>First catalyst - Osmium</h2>
    <p>
      The first catalyst haber used was osmium. Haber found that at a
      temperature 600c and 200 atm of pressure a yield of 18% could be made.
      Osmium is a transition element which typically make good catalysts, this
      is they have two valence electrons in its valence shell, this allows them
      to give and take electrons easily, which makes them good catalysts. The
      problem with osmium is that it is very expensive and rare. It only
      accounts for 50 parts per trillion of earth's crust. This makes it
      unsuitable for mass production. Osmium hasn’t been used long enough to get
      detailed data on it.
    </p>
    <h2>Iron promoted</h2>
    <p>
      After his discovery, his process was bought by the German chemical company
      BASF where Bosch was put in charge of scaling the process up for
      industrial scale. This meant changing the osmium to iron. The change from
      iron to osmium added an unexpected twist. “[It] is remarkable how … new
      special features always come to light. Here iron, with which Ostwald had
      first worked and which we later tested a hundred times in its pure state,
      is now found to function when impure”, as Haber stated. Haber made use of
      Swedish iron ore which contains aluminum and potassium impurities. Instead
      of poisoning the catalyst it acts as a promoter, improving the efficiency.
    </p>
    <h2>Ruthenium</h2>
    <p>
      Later in the 1990s Kellog started using ruthenium based catalysts,
      supported on an activated carbon complex. Ruthenium is a highly reactive
      element, so the pressure can be lowered to around a third of an iron based
      catalyst. 150-300 bars reverse 70-105 bars of pressure. Ruthenium is a
      more expensive element than iron but most of the catalyst is carbon so the
      cost can be brought down. Ruthenium typically makes up 2-10% of the
      overall catalyst blend. Today Ruthenium catalysts are the second most
      common for the haber process.
    </p>
    <h2>References</h2>
    <ol class="references">
      <li>
        Friedrich, Bretislav. “A Brief Biography of Fritz Haber (1868-1934).”
        Brief Bio of Fritz Haber,
        <a href="https://www.fhi.mpg.de/70309/History_Brief_Bio_Haber.pdf"
          >www.fhi.mpg.de/70309/History_Brief_Bio_Haber.pdf</a
        >. Accessed 8 Mar. 2024.
      </li>
      <li>
        Rosowski, Frank, et al. “Ruthenium Catalysts for Ammonia Synthesis at
        High Pressures: Preparation, Characterization, and Power-Law Kinetics.”
        Applied Catalysis A: General, vol. 151, no. 2, Elsevier BV, Apr. 1997,
        pp. 443–60, <a href="https://doi.org/10.1016/s0926-860x(96)00304-3"
          >https://doi.org/10.1016/s0926-860x(96)00304-3</a
        >. Accessed 7 Mar. 2024.
      </li>
      <li>
        Humphreys, John, et al. “Development and Recent Progress on Ammonia
        Synthesis Catalysts for Haber–Bosch Process.” Advanced Energy and
        Sustainability Research, vol. 2, no. 1, Wiley, Dec. 2020,
        <a href="https://doi.org/10.1002/aesr.202000043"
          >https://doi.org/10.1002/aesr.202000043</a
        >. Accessed 7 Mar. 2024.
      </li>
    </ol>
  </div>
</main>

<style>
  .main {
    padding: 20px;
    max-width: 800px;
    box-sizing: border-box;
  }
  .references li {
    padding: 10px;
  }
</style>
