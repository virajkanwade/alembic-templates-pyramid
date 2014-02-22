alembic-templates-pyramid
=========================

Pyramid template for alembic

Installation:
-------------
Install alembic using "pip install alembic".

Find the location of alembic install directory.

Copy "pyramid" folder to "[alembic_dir]/templates/"

Usage:
------
"alembic list_templates" should list pyramid as a template option

"alembic init --template pyramid alembic"

Make sure the "Base" object from "models " is available as "from [proj].models import Base"
