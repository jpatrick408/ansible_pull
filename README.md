#ansible-pull

This is a generic version of my Ansible Pull playbook for setting up/restoring systems in my home lab.  If you want to use it, please review each section and update it to your needs.  Pay special attention to the areas with [BRACKETS].  You will need to replace the text there with your personal settings.

If you have questions, please let me know and I will do my best to assist.

This is an active project but it is not updated frequently.   What I have here is mostly stable and will only be updated when I haved new machines to deploy or there is an update in the way something works.


- Most of what I have learned came from the following:
    - Online Documentation
      - https://docs.ansible.com/
    - Jay LaCroix at learnlinux.tv
      - https://www.youtube.com/watch?v=3RiVKs8GHYQ&list=PLT98CRl2KxKEUHie1m24-wkyHpEsa4Y70
      - Jay's opensource.com Ansible Articles
        - Part 1: https://opensource.com/article/18/3/manage-workstation-ansible
        - Part 2: https://opensource.com/article/18/3/manage-your-workstation-configuration-ansible-part-2
        - Part 3: https://opensource.com/article/18/5/manage-your-workstation-ansible-part-3
    - Claudio Kuenzler's Blog on getting the lates version of a GitHub package
      - https://www.claudiokuenzler.com/blog/1361/how-to-retrieve-latest-version-tag-github-repository-api-ansible-playbook
    - Techno Tim
      - https://www.youtube.com/watch?v=w9eCU4bGgjQ
    - Google
      - There are a couple other sources not mentioned.  For those sources, I left comments in the playbooks.
