command /cchatclear:

    trigger:

        if player is not op:

            send "&cYou do not have permission."

            stop



        loop all players:

            loop 150 times:

                send "" to loop-player



        broadcast "&7[&bServer&7] &aChat has been cleared by &e%player%&a!"

