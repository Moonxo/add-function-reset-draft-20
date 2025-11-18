# add-function-reset-draft-20
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
