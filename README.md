# hello-google-ignite
First repo for Google Ignite
I look forward to the first Workshop!


// Check availability
bool isAvailable = await NfcManager.instance.isAvailable();

// Start Session
NfcManager.instance.startSession(
  onDiscovered: (NfcTag tag) async {
    // Do something with an NfcTag instance.
  },
);

// Stop Session
NfcManager.instance.stopSession();
