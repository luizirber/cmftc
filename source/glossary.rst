********
Glossary
********

In this section you will find all the terms I stumbled upon while reading papers
and didn't know what they mean. Each term has two sections: First guess, where I
try to explain it without looking for the correct definition and using just the
context, and Definition, explained by some especialist or found at technical
literature.

.. glossary::
  :sorted:

  Climatological wind speed
    First guess:
      Not a clue.
    Definition:
      Explained by [Roberto de Almeida]_ : 

  Spinup
    First guess:
      Process where you give some historical input to the model, to train it
      before running the simulation.

    Definition:
      Explained by [Roberto de Almeida]_ : the model starts at rest state, and
      it runs for some time (~500 years) with an :term:`climatological wind speed`
      (or another variable) to start fluid motion. He gave an example: if you want
      to run a prediction starting at 1990, you let the model run for some time and
      at some point start putting the real values for wind speed (ten years before
      the start, for example) to 'train' the model and make it converge, so the
      predictions are accurate.

  General Circulation Model (GCM)
    First guess:
      It's a type of model. Paper cites atmospheric and ocean versions.

    Definition:
      TODO

  Ensemble
    First guess:
      Not a clue. "10-member ensemble average"?

    Definition:
      TODO

  Spectral global model
    First guess:
      Not a clue.

    Definition:
      TODO

  Triangular truncation
    First guess:
      Not a clue.

    Definition:
      TODO

  Wavenumber
    First guess:
      Not a clue. References :term:`sigma level`.

    Definition:
      TODO

  Sigma level
    First guess:
      Not a clue. Can be unevenly spaced, and in the vertical.

    Definition:
      TODO

  Surface scheme
    First guess:
      Seems to be the part of the model that represents ground level processes
      that influences the simulation. Example: :term:`Simplified Simple
      Biosphere Model`

    Definition:
      TODO

..  template
    First guess:
      Not a clue.
    Definition:
      TODO

