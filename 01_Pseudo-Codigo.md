* If the location has an item required to enter it
  * If the player does not have the item
     * Display message
     * Don't let the player move here (stop processing the move)
* Update the player's current location
  * Display location name and description
  * Show/hide the available movement buttons
* Completely heal the player (we assume they rested/healed while moving)
  * Update hit points display in UI
* Does the location have a quest?
  * If so, does the player already have the quest?
     * If so, is the quest already completed?
       * If not, does the player have the items to complete the quest?
         * If so, complete the quest
           * Display messages
           * Remove quest completion items from inventory
           * Give quest rewards
           * Mark player's quest as completed
     * If not, give the player the quest
       * Display message
       * Add quest to player quest list
* Is there a monster at the location?
  * If so,
     * Display message
     * Spawn new monster to fight
     * Display combat comboboxes and buttons
       * Repopulate comboboxes, in case inventory changed
  * If not
     * Hide combat comboboxes and buttons
* Refresh the player's inventory in the UI – in case it changed
* Refresh the player's quest list in the UI – in case it changed
* Refresh the cboWeapons ComboBox in the UI
* Refresh the cboPotions ComboBox in the UI
