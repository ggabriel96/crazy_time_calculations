# crazy_time_calculations
A little crazy program that takes a String with a query to convert some time info and tries to interpret and answer it (approximately). This code assumes 365 days for a year and 30 days for a month. **This is experimental code.**

Currently, the only kind of input that gets answered is in Portuguese and follows the pattern:

`<x> [in] <period>`, e.g.: "quantos meses há em 8 semanas e 30 dias?".

* `<x>` can be: segundos, minutos, horas, dias, semanas, meses, anos (case-insensitive, singular or plural. Accents not supported);
* `[in]` is optional. Means: existem em, há em, em, tem. Accents doesn't matter here;
* `<period>` can be things like: 11 anos, 7 meses, 5 semanas e 37 dias...;
* All other text around it doesn't matter if it's not related to the core of the query or time.
