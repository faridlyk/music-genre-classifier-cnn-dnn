# Music Genre Classification witn CNN and DNN

This project uses a combination of audio features and mel spectrograms to classify music into 10 different genres: blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, and rock.

## Model

The model is a hybrid model that combines a dense neural network for audio features and a convolutional neural network for mel spectrograms. The audio features are extracted using the Librosa library, and the mel spectrograms are generated using the same library. The model is trained using the GTZAN dataset.

## Results

The model achieves an accuracy of around 79.50% on the GTZAN dataset.

## License

This project is licensed under the MIT License.
