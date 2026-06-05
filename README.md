# Lab8-Starter
William Wang

Graceful degradation and service workers are closely related because service workers are one of the primary tools we use to implement graceful degradation in web applications. Without service workers, losing network access would mean losing the entire application. With them, we degrade gracefully from "full network access" down to "fully offline," ensuring that users are never left with a broken empty page.