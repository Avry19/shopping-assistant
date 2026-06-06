# Shopping Assistant Experiment

This repository contains a rule-based shopping assistant for a 2 × 2 experiment.

## Conditions

- cute_warm
- cute_task
- notcute_warm
- notcute_task

## Main page

The experiment runs from:

https://avry19.github.io/shopping-assistant/

## Condition URLs

https://avry19.github.io/shopping-assistant/?condition=cute_warm

https://avry19.github.io/shopping-assistant/?condition=cute_task

https://avry19.github.io/shopping-assistant/?condition=notcute_warm

https://avry19.github.io/shopping-assistant/?condition=notcute_task

## Qualtrics iframe format

```html
<iframe
  src="https://avry19.github.io/shopping-assistant/?pid=${e://Field/ResponseID}&condition=${e://Field/condition}"
  width="100%"
  height="760"
  style="border:0; border-radius:16px;">
</iframe>
