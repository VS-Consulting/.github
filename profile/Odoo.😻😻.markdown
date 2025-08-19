# Fork, Commit & Merge

![](https://github.com/user-attachments/assets/fe3fc135-b851-435a-9979-d3b1299e5338)

As we said earlier, in the digital world we can create copies.
Copies can be updated, and each update is called a *commit*.

Imagine you are working on the blueprint for a renovated Oval Office. The
blueprint includes a line of code: the URL to the painting above the fireplace.
You decide to update the artwork. You replace the URL, and you *make a commit*.
That means you haven’t torn down the office—you’ve simply adjusted the plan,
adding a note that clarifies what already exists.

Now, in programming we go a step further: we make a *fork*. Why is it called a
fork? Because the existing project is already a long chain of commits—a series
of changes that transformed an empty folder into a living project. When we
create a fork, we copy that history and then add new commits. Suddenly, we have
two slightly different versions branching out from the same root. If you draw it
on paper, you’ll see a common history, then two diverging lines—that’s a fork.

Later comes the *merge*. That’s when the features of one copy are united back
into a single final project. Like two parallel stories converging into one
ending.

But with Odoo, there’s another layer of complexity. We don’t just fork the
project (the office itself), we also fork the database—the list of
people who work in the White House, their roles, and their data.

What You Need to Understand About Database Copies in Odoo.

* **Production** — the real Oval Office (standard + custom modules) with the final list of staff (live database).
* **Staging** — a fork of the office *with* a copied list of staff (clone of the database).
* **Development** — a partial copy of the office (not every module installed), *without* a copy of real staff—only a minimal demo team in the database.

➡️ On the [next slides,](Odoo.😻😻😻.markdown) we’ll provide full technical details of development and how we keep all these copies in sync.

