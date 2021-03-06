========================
Installation on openSUSE
========================

1.  Install the Kolab Groupware repositories:

    *   For openSUSE 13.1:

        .. parsed-literal::

            # :command:`zypper ar http://obs.kolabsys.com/repositories/Kolab:/3.3/openSUSE_13.1/Kolab:3.3.repo`
            # :command:`zypper ar http://obs.kolabsys.com/repositories/Kolab:/3.3:/Updates/openSUSE_13.1/Kolab:3.3:Updates.repo`

    *   For openSUSE 12.3:

        .. parsed-literal::

            # :command:`zypper ar http://obs.kolabsys.com/repositories/Kolab:/3.3/openSUSE_12.3/Kolab:3.3.repo`
            # :command:`zypper ar http://obs.kolabsys.com/repositories/Kolab:/3.3:/Updates/openSUSE_12.3/Kolab:3.3:Updates.repo`

    *   For openSUSE 12.2:

        .. parsed-literal::

            # :command:`zypper ar http://obs.kolabsys.com/repositories/Kolab:/3.3/openSUSE_12.2/Kolab:3.3.repo`
            # :command:`zypper ar http://obs.kolabsys.com/repositories/Kolab:/3.3:/Updates/openSUSE_12.2/Kolab:3.3:Updates.repo`

2.  Install Kolab Groupware:

    .. parsed-literal::

        # :command:`zypper in kolab`

Continue to :ref:`install-setup-kolab`.
