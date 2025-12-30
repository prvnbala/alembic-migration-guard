# alembic-migration-guard
A GUI tool that analyzes Alembic scripts for 'Dangerous Operations' (like dropping a column without a backup) and runs automated Up/Down integrity tests.

## Safety
**Disclaimer**: This tool is designed to enhance development workflows and identify common migration risks. It is a supplement to, not a replacement for, standard database administration practices. Always perform a full database backup before running migrations in a production environment. The authors are not responsible for any data loss resulting from the use of this software.
