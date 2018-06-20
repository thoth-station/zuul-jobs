Runs pipenv for a project

**Role Variables**

.. zuul:rolevar:: pipenv_environment

   Environment variables to pass in to the pipenv run.

.. zuul:rolevar:: pipenv_executable
   :default: pipenv

   Location of the pipenv executable.

.. zuul:rolevar:: pipenv_extra_args
   :default:

   String of extra command line options to pass to pipenv.

.. zuul:rolevar:: zuul_work_dir
   :default: {{ zuul.project.src_dir }}

   Directory to run pipenv in.
