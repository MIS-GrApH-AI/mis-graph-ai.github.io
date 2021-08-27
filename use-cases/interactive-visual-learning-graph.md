---
layout: default
---

<a href="{{ "/" | relative_url }}">{{ site.theme_config.back_home_text }}</a>

<header>
  <h1>Design and develop clinical health assisted intelligence via an interactive visual knowledge graph
</h1>
</header>

As a knowledge seeker looking to expand capabilities in the clinical health field of endeavor

I want to help cultivate and refine a knowledge graph data set, focused on diagnosis, interventions and outcomes using the MIMIC III core data and any pertinent reference corpus, dictionaries, libraries in order to make this solution available through an interactive visual mechanism (e.g. web app, AR app)

so that a user, such as a clinician, can traverse the graph to assist in exploring and evaluating healthcare options for a patient

Acceptance criteria and considerations:

    Graph should be simple and follow the PAR form: Problem -> Action -> Result

        Problem for clinical health may follow the pattern: locus -> bodypart -> ailment (e.g. upper GI bleed)

        Action can be an individual intervention action or a sequence/regiment of intervention actions

        Result would be reduction or elimination of the ailment; likely expressed as a probability (may also specify risks/side effects and their probabilities)

    Solution can be a functional prototype; this can help focus research and design (need to consider how solution will be used)

        User should be able to select a body part or ailment (may be a whole body symptom such as fatigue); may need to use an anatomy hierarchy or image in order to help the user quickly narrow in on a body part

        Zooming in can allow narrower focus (e.g. initially select abdomen area, then isolate an organ, then section of organ such as upper GI tract); need to keep number of gestures/clicks low

        If multiple Action alternatives are available, need to come up with ranking mechanism (e.g. risk/benefit weighted)

        Can use ranking mechanism to order problems/ailments with most common coming up first

Contributors: Dan Rigoli

Join the discussion [here](https://github.com/MIS-GrApH-AI/mis-graph-ai.github.io/discussions/15).