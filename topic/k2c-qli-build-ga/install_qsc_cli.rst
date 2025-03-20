.. _install_qsc_cli:

Install QSC CLI
--------------------

1. Install curl (if not installed already):

   .. container:: nohighlight
      
      ::

         sudo apt install curl

2. Download the Debian package for ``qsc-cli``:

   .. container:: nohighlight
      
      ::

         cd <workspace_path>
         curl -L https://softwarecenter.qualcomm.com/api/download/software/qsc/linux/latest.deb -o qsc_installer.deb

3. Install the ``qsc-cli`` Debian package:

   .. container:: nohighlight
      
      ::

         sudo apt update
         sudo apt install ./qsc_installer.deb

4. Sign in to ``qsc-cli`` using your registered email ID:

   .. note:: To register, go to https://www.qualcomm.com/support/working-with-qualcomm.

   .. container:: nohighlight
      
      ::

         qsc-cli login -u <username>

.. note:: For more information, see ``qsc-cli`` related topics in :ref:`How to Sync <howto_sync>`.