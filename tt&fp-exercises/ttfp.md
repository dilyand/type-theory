1.1. Give a proof of the transitivity of implication, by showing that we can derive $A ⇒ C$ from the assumptions $A ⇒ B$ and $B ⇒ C$.

$$
\cfrac {\cfrac {\cfrac {[A]^1 \>\>\>\> A ⇒ B \>\>\>\> B ⇒ C}{B \>\>\>\> B ⇒ C}{\rm (⇒ E)}}{C}{\rm (⇒ E)}}{A ⇒ C}{\rm (⇒ I)_1}
$$

1.2. Give a proof of $((A ∨ B) ⇒ C) ⇒ ((A ⇒ C) ∧ (B ⇒ C))$.

$$
\cfrac {\cfrac {\cfrac {\cfrac {\cfrac {[A]^1}{A ∨ B}{\rm (∨ I_1)} \>\>\>\> [(A ∨ B) ⇒ C]^3}{C}{\rm (⇒ E)}}{A ⇒ C}{\rm (⇒ I)_1} \>\>\>\>\>\>\> \cfrac {\cfrac {\cfrac {[B]^2}{(A ∨ B)}{\rm (∨ I_2)} \>\>\>\> [(A ∨ B) ⇒ C]^3}{C}{\rm (⇒ E)}}{B ⇒ C}{\rm (⇒ I)_2}}{(A ⇒ C) ∧ (B ⇒ C)}{\rm (∧ I)}}{((A ∨ B) ⇒ C) ⇒ ((A ⇒ C) ∧ (B ⇒ C))}{\rm (⇒ I)_3}
$$

1.3. Give a proof of $(A ⇒ (B ⇒ C)) ⇒ ((A ∧ B) ⇒ C)$.

$$
\cfrac {\cfrac {\cfrac {\cfrac {[A ∧ B]^1}{B}{\rm (∧ E_2)} \>\>\>\> \cfrac {\cfrac {[A ∧ B]^1}{A}{\rm (∧ E_1)} \>\>\>\> [A ⇒ (B ⇒ C)]^2}{B ⇒ C}{\rm (⇒ E)}}{C}{\rm (⇒ E)}}{(A ∧ B) ⇒ C}{\rm (⇒ I)_1}}{(A ⇒ (B ⇒ C)) ⇒ ((A ∧ B) ⇒ C)}{\rm (⇒ I)_2}
$$
