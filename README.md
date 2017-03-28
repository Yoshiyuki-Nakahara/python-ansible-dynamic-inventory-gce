# ansible-dynamic-inventory-gcp
Since it may be troublesome that information such as tag, status, zone, etc. is included in the group information of the output contents of gcp.py, it is improved so that the output content can be controlled

# References
[Ansible Dynamic Inventory Programs](https://github.com/ansible/ansible/tree/devel/contrib/inventory)

# Configuration (Additional)
    # gce.ini

    inventory_group_zone = (yes|no)
    inventory_group_instance_tags = (yes|no)
    inventory_group_instance_tags_prefix = tag_
    inventory_group_network_name = (yes|no)
    inventory_group_machine_type = (yes|no)
    inventory_group_running_status = (yes|no)
    inventory_group_running_status_prefix = status_
    inventory_group_image = (yes|no)
