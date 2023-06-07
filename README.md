import random
from music21 import stream, note, duration

def generate_music(num_notes):
     notes = ['C', 'D', 'E', 'F', 'G', 'A', 'B']
     durations = [0.25, 0.5, 0.75, 1, 1.5, 2]
     
     music_stream = stream.Stream()
     
     for _ in range(num_notes):
     
         random_note = random.choice(notes)
         random_duration = random.choice(durations)
         
         note_obj = note.Note(random_note)
         note_obj.duration = duration.Duration(random_duration)
         
         music_stream.append(note_ob
         generated_music =
         generate_music(10) generated_music.show()
