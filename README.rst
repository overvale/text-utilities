A small collection of utilities for transforming text.

----

:abbreviation: Very simple script that adds periods for abbriviations. nasa => N.A.S.A.
:list-numbered: Makes lines into a numbered list.
:titlecase: Make text titlecase.
:wraplist78: Wraps lists to 78 characters. Requires pandoc.


``clause-break`` and ``clause-join`` are useful if you write hard-wrapped paragraphs with newlines at breaks between clauses.

Given the following (which is very easy to type and version-control)::

    the cat,
    which was not mine but my brother's,
    lay on the bed.
    the dog,
    which was my father's,
    lay in the corner.
    I didn't like my family
    but I liked the pets.

``clause-join`` will produce this:

    The cat, which was not mine but my brother's, lay on the bed. The dog, which was my father's, lay in the corner. I didn't like my family but I liked the pets.
