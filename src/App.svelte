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
  </div>
</main>

<style>
  .main {
    padding: 20px;
    max-width: 800px;
    box-sizing: border-box;
  }
</style>
