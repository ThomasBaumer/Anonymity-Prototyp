# Anonymity-Prototyp
A prototyp for demonstrating some anonymization techniques.

## Motivation - Why do I need this?
This prototype provides a first impression of anonymization techniques.

It implements a Noise Addition algorithm and a _k_-anonymity algorithm.

## Requirements
The server programm (Anonymity) is written in C#. Therefore it runs on Microsoft Windows.

The client programm is written in Java.

The client programm sends CybOX objects (Email and IP-addresses) to anonymity via the local host.

## Usage
1. Start Anonymity.
2. Choose your settings.
    1. _n_: The anonymization starts, when _n_ objects reach Anonymity.
    2. policy: choose Noise Addition or _k_-anonymity. By choosing Noise Addition you have to set the strength of the noise (1%-10%) and by choosing _k_-anonymity you have to set the groupsize _k_ and the generalization strategy.
3. Start the client.
4. Choose one sample (or your own) CybOX object and send it to Anonymity.
5. By sending _n_ objects to Anonymity the anonymization takes place and the result will be shown.
  
